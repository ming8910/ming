# ming
my warehouse
The first day warehouse
     Download the softwares
        1.Arduino
        2.Fritzing
        3.processing 
     Looking through the github.com
        learn by myself
     introduction for open source software and hardware
The second day warehouse
     Learn materials from DaMo
     write the Morse code library
     write the Morse code in the library way
#include "Arduino.h"
#include "Morse.h"
#define Morse_h 
Morse::Morse(int pin)
{
  pinMode(pin,OUTPUT);
  _pin=pin;
  _dottime=250;
}

void Morse::dot()
{
  digitalWrite(_pin,HIGH);
  delay(_dottime);
  digitalWrite(_pin,LOW);
  delay(_dottime);
}

void Morse::dash()
{
  digitalWrite(_pin,HIGH);
  delay(_dottime*4);
  digitalWrite(_pin,LOW);
  delay(_dottime);
}
void Morse::c_space()
{
 digitalWrite(_pin,LOW);
 delay(_dottime*3);
}
void Morse::w_space()
{
  digitalWrite(_pin,LOW);
  delay(_dottime*7);
}
void loop()//a
{
  morse.dot();
  morse.dash(); 
  delay(3000); 
}
void loop()//b
{
  morse.dash(); 
  morse.dot();
  morse.dot();
  morse.dot();
  delay(3000);
}
void loop()//c
{
  morse.dash(); 
  morse.dot();
  morse.dash(); 
  morse.dot();
  delay(3000);
}

void loop()//d
{
  morse.dash();
  morse.dot();
  morse.dot();
  delay(3000);
}

void loop()//e
{
 morse.dot();
 delay(3000);
}

void loop()//f
{
 morse.dot();
 morse.dot();
 morse.dash();
 morse.dot();
 delay(3000);
}

void loop()//g
{
 morse.dash();
 morse.dash();
 morse.dot();
 delay(3000);
}

void loop()//h
{
 morse.dot();
 morse.dot();
 morse.dot();
 morse.dot();
 delay(3000);
}

void loop()//i
{
 morse.dot();
 morse.dot();
 delay(3000);
}

void loop()//j
{
  morse.dot();
  morse.dash();
  morse.dash();
  morse.dash();
  delay(3000);
}

void loop()//k
{
 morse.dash();
 morse.dot();
 morse.dash();
 delay(3000);
}

void loop()//l
{
   morse.dot();
   morse.dash();
   morse.dot();
   morse.dot();
   delay(3000);
}

void loop()//m
{
 morse.dash();
 morse.dash();
 delay(3000);
}

void loop()//n
{
   morse.dash();
   morse.dot();
   delay(3000);
}

void loop()//o
{
  morse.dash(); 
  morse.dash(); 
  morse.dash();
  delay(3000);
}

void loop()//p
{
  morse.dot();
  morse.dash();
  morse.dash(); 
  morse.dot();
  delay(3000);
}

void loop()//q
{
  morse.dash(); 
  morse.dash();
  morse.dot();
  morse.dash();
  delay(3000);
}

void loop()//r
{
   morse.dot();
   morse.dash();
   morse.dot();
   delay(3000);
}

void loop()//s
{
  morse.dot();
  morse.dot();
  morse.dot();
  delay(3000);
}


void loop()//t
{
 morse.dash();
 delay(3000);
}

void loop()//u
{
  morse.dot();
  morse.dot();
  morse.dash();
  delay(3000);
}

void loop()//v
{
   morse.dot();
   morse.dot();
   morse.dot();
   morse.dash(); 
   delay(3000);
}

void loop()//w
{
   morse.dot(); 
   morse.dash();  
   morse.dash(); 
   delay(3000); 
}

void loop()//x
{
  morse.dash();
  morse.dot();
  morse.dot(); 
  morse.dash(); 
  delay(3000); 
}

void loop()//y
{
   morse.dash();
   morse.dot();
   morse.dash(); 
   morse.dash(); 
   delay(3000);  
}

void loop()//z
{
  morse.dash();
  morse.dash();
  morse.dot();
  morse.dot();
  delay(3000); 
}

The third day warehouse
     Draw analog circuit board(motor)
     write the program
/*
void setup()

{

   pinMode(5, OUTPUT);

   pinMode(6, OUTPUT);

   pinMode(10, OUTPUT);

   pinMode(11, OUTPUT);

   Serial.begin(9600);

}



int income();



void loop()

{

  if(Serial.available()>0){

     income=Serial.read();

  }

  switch(income){

    case:'f':

        forward();

    break;

    

    case:'b':

        backward();

    break;

    

    case:'l':

        left();

    break;

    

    case:'r':

        right();

    break;

    

    case:'s':

        stop();

    break;

    

    default;

    break;

  }

}



void forward(){

  digitalWrite(5,HIGH);

  digitalWrite(6,LOW);

  digitalWrite(11,HIGH);

  digitalWrite(10.LOW);

}



void backward(){

  digitalWrite(5,HIGH);

  digitalWrite(6,LOW);

  digitalWrite(10,HIGH);

  digitalWrite(11.LOW);

}



void left(){

  digitalWrite(5,HIGH);

  digitalWrite(6,LOW);

  digitalWrite(11,HIGH);

  digitalWrite(10.LOW);

}



void right(){

  digitalWrite(6,HIGH);

  digitalWrite(5,LOW);

  digitalWrite(10,HIGH);

  digitalWrite(11.LOW);

}



void stop(){

  digitalWrite(6,LOW);

  digitalWrite(5,LOW);

  digitalWrite(10,LOW);

  digitalWrite(11.LOW);

}
*/Draw analog circuit board include chip
     write the program
/*


*/
The last day
         Draw analog circuit board includes 4 chips
         write the program


*/

