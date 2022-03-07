#include<LiquidCrystal.h>
LiquidCrystal lcd(13,12,11,10,9,8);

#define fan A0
#define light 2
#define tv 6
#define motor A1

char a[5],data,m;
int acta=0,actb=0,actc=0,actd=0;

void setup()
{
  Serial.begin(9600);
  lcd.begin(16,2);
  
  pinMode(fan,OUTPUT);
  pinMode(light,OUTPUT);
  pinMode(motor,OUTPUT);
  pinMode(tv,OUTPUT);

  digitalWrite(motor,LOW);
  digitalWrite(fan,LOW);
  digitalWrite(light,LOW);
  digitalWrite(tv,LOW);

  lcd.setCursor(0,0);
  lcd.print("HOME");
  lcd.setCursor(0,1);
  lcd.print("AUTOMATION");
  delay(2000);
  lcd.clear(); 
}
void loop()
{   
  receive_();
  lcd.setCursor(0,0);
  lcd.print("HOME");
  lcd.setCursor(0,1);
  lcd.print("AUTOMATION");
}

  if(m >= 2)
   {
      if(a[1] == 'A')
       {
          acta=acta+1;
          delay(100);
      if(acta >= 2)
        {
         acta=0;
        }
      } 
 if(a[1] == 'B')
    {
      actb=actb+1;
      delay(100);
      if(actb >= 2)
      {
        actb=0;
      }
    }
  if(a[1] == 'C')
    {
      actc=actc+1;
      delay(100);
      if(actc >= 2)
       {
         actc=0;
       }
    }
  if(a[1] == 'D')
    {
      actd=actd+1;
      delay(100);
      if(actd >= 2)
    {
      actd=0;
     }
     }
     m=0;

 if(acta == 1)
   {
     lcd.setCursor(0,0);
     lcd.print("FAN ON"); 
     digitalWrite(fan,HIGH);
     delay(1000);
   }
 else
  { 
     lcd.setCursor(0,0);
     lcd.print("FAN OFF");
     digitalWrite(fan,LOW);
     delay(1000);
   }
  if(actb == 1)
    {
         lcd.setCursor(0,0);
         lcd.print("LIGHT ON");
         digitalWrite(light,HIGH);
         delay(1000);
     }
   else
   {
         lcd.setCursor(0,0);
         lcd.print("LIGHT OFF");
         digitalWrite(light,LOW);
         delay(1000);
    }
   if(actc == 1)
     { 
       digitalWrite(tv,HIGH);
       lcd.setCursor(0,0); 
       lcd.print("MOTOR ON"); 
       delay(1000);
     }
   else 
     {
        lcd.setCursor(0,0);
        lcd.print("MOTOR OFF");
        digitalWrite(tv,LOW);
        delay(1000);
     }
    

 if(actd == 1)
     {
         digitalWrite(motor,HIGH);
         lcd.setCursor(0,0); 
         lcd.print("TV ON");
         delay(1000);
    }
 else
   {
       digitalWrite(motor,LOW);
       lcd.setCursor(0,0);
       lcd.print("TV OFF");
       delay(1000);
    }
  }    
}
void receive_()
{
    while(Serial.available())
    {
        char data;
        data = Serial.read();
          a[m]=data;
          if(a[0] = = '*')
           {
              if(m < 3)
            {
               m++;
             }
          }
     }
}


 




