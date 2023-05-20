#DAY-1# 10 day internship
**day-1**
>github
1. create a public acc.
2. create a new file
3. create your repository
> uses of symbols
- "#" used for big size
- "**" used for bold size
- "*" used for small size
- ".n" used for order list
- "-" used for dot
- "```"used for code or copy able


```
fileptr=open("file1text","w")
fileptr.write("python is a modern lanuage")
fileptr.close()
```
> link linking
1. [shinto](https://github.com/2003SHINTO)
>linking image
-create a file
![alt electron](https://github.com/kumarkrishna2003/10-days-internship/blob/main/img/Untitled.jpeg)

#DAY-2
>TINKER CADED
_CREATED ACC
- CREATED NEW CIRCIUT
- USING TINKER CADED LED GLOW CIRCUIT IN BREAD BOARD 
![alt sorry](https://github.com/kumarkrishna2003/10-days-internship/blob/main/img/Screenshot%20from%202023-05-09%2012-09-52.png)
>led glow using switch
![alt sorry](https://github.com/kumarkrishna2003/10-days-internship/blob/main/img/Screenshot%20from%202023-05-09%2012-16-09.png)
[tinker cade](https://www.tinkercad.com/things/08pXx94FczB-led-glowing-using-varable-resistor)
# day3
- tinkering cade 
- using logic gate and gate
1. AND gate verfication 
![alt simulatio](https://github.com/kumarkrishna2003/10-days-internship/blob/main/Screenshot%20from%202023-05-11%2010-17-30.png)
> circuit schematic
![alt circuit schematic](https://github.com/kumarkrishna2003/10-days-internship/blob/main/Screenshot%20from%202023-05-11%2010-26-38.png)
![alt component list](https://github.com/kumarkrishna2003/10-days-internship/blob/main/img/Screenshot%20from%202023-05-11%2010-26-41.png)
2.arduino interfacing
- led blinking
![alt arduino](https://github.com/kumarkrishna2003/10-days-internship/blob/main/Screenshot%20from%202023-05-11%2011-29-08.png)
![alt arduino](https://github.com/kumarkrishna2003/10-days-internship/blob/main/Screenshot%20from%202023-05-11%2011-28-48.png)
#code for blinking led
```
// C++ code
//
void setup()
{
  pinMode(8, OUTPUT);
}

void loop()
{
  digitalWrite(8, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(8, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
```
[arduino interfacing1](https://www.tinkercad.com/things/bL3zKL1EtSU-arduino-interfacing1)
# arduino 
- arduino has digital and analog write and read 
- adrduino 2 led blinking
![alt astable](https://github.com/kumarkrishna2003/10-days-internship/blob/main/Screenshot%20from%202023-05-11%2012-38-18.png)
![alt astable](https://github.com/kumarkrishna2003/10-days-internship/blob/main/Screenshot%20from%202023-05-11%2012-38-20.png)
# code for astable mode operation
```
// C++ code
//
void setup()
{
  pinMode(12, OUTPUT); 
  pinMode(7, OUTPUT);
      
}

void loop()
{
  digitalWrite(12, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(12, LOW);// Wait for 1000 millisecond(s)
  digitalWrite(7, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(7, LOW);// Wait for 1000 millisecond(s)
  
}
```
>DANCING LIGHT
![alt img](https://github.com/kumarkrishna2003/10-days-internship/blob/main/Screenshot%20from%202023-05-11%2015-43-15.png)
- CODE FOR DANCING LIGHT
```
// C++ code
//
void setup()
{
   pinMode(13, OUTPUT);
   pinMode(12, OUTPUT);
   pinMode(8, OUTPUT);
   pinMode(7, OUTPUT);
   pinMode(4, OUTPUT);

}

void loop()
{
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(13, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(12, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(12, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(8, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(8, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(7, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(7, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(4, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(4, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(13, HIGH);
  digitalWrite(12, HIGH);
  digitalWrite(8, HIGH);
  digitalWrite(7, HIGH);
  digitalWrite(4, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(13, LOW);
  digitalWrite(12, LOW);
  digitalWrite(8, LOW);
  digitalWrite(7, LOW);
  digitalWrite(4, LOW);
  delay(2000);
  digitalWrite(13, HIGH);
  digitalWrite(12, HIGH);
  digitalWrite(8, HIGH);
  digitalWrite(7, HIGH);
  digitalWrite(4, HIGH);
  
}
```
[THINKERTHIS](https://www.tinkercad.com/things/ft6hrPTffez-dancing-light)
- 7 segament display using arduino
![alt 7seg](https://github.com/kumarkrishna2003/10-days-internship/blob/main/Screenshot%20from%202023-05-15%2014-36-22.png)
>code for 7 segament

```
// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(12,OUTPUT);
  pinMode(11,OUTPUT);
  pinMode(10,OUTPUT);
  pinMode(9,OUTPUT);
  pinMode(8,OUTPUT);
  pinMode(7,OUTPUT);
}

void loop()
{
  digitalWrite(13, LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,HIGH);
  delay(1000); // Wait for 1000 millisecond(s
  digitalWrite(11,LOW);
  digitalWrite(12,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(13,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(1000);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,LOW);
  digitalWrite(10,LOW);
  digitalWrite(8,HIGH);
  digitalWrite(11,HIGH);
  delay(1000);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  delay(1000);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(13,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(10,HIGH);
  delay(1000);
  digitalWrite(13,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(12,HIGH);
  delay(1000);
  digitalWrite(13,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(12,HIGH);
  delay(1000);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(1000);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  delay(1000);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  delay(1000);
  
  delay(1000); // Wait for 1000 millisecond(s)
}

```
[thinker this](https://www.tinkercad.com/things/f5GIdlII1CW-7-segament-display-using-arduino-board)
# day-4
- machine learning
- base of code
- using blockly
- made print sum of 2 number using blockly
- made calcaluator using if function
- machine learning
- using sim 32 nucled development board
- recorded by 2 audio in board
- baby cry and ambulance
- machine recovered voice as baby cry and ambulance
![alt img2](https://github.com/kumarkrishna2003/10-days-internship/blob/main/Screenshot%20from%202023-05-12%2012-08-29.png)
![alt img3](https://github.com/kumarkrishna2003/10-days-internship/blob/main/Screenshot%20from%202023-05-12%2012-24-09.png)
# day-5 
- drone induction 
- parts of drone
- different type of drone
- arduino  analog input using potential meter
![alt img](https://github.com/kumarkrishna2003/10-days-internship/blob/main/Screenshot%20from%202023-05-15%2014-37-57.png)
![alt img](https://github.com/kumarkrishna2003/10-days-internship/blob/main/Screenshot%20from%202023-05-18%2009-12-04.png)
# day-6
- 3d printer
- parts of 3d printer
- working of printer
- created 3d block in tinker cade
![alt img](https://github.com/kumarkrishna2003/10-days-internship/blob/main/img/Screenshot%20from%202023-05-18%2009-17-31.png)
![alt img](https://github.com/kumarkrishna2003/10-days-internship/blob/main/Screenshot%20from%202023-05-18%2009-18-10.png)
# day-7
- lab visiting
- electrical lab
- electronic lab
- robotic introduction
- types of robot
- working of robot
- controling of robot
# day -8
> arduino analog inferencing speed caontrolled by pot
```// C++ code
const int potPin = A0;

void setup()
{
  Serial.begin(9600);
  pinMode(13, OUTPUT);
  pinMode(12,OUTPUT);
  pinMode(11,OUTPUT);
  pinMode(10,OUTPUT);
  pinMode(9,OUTPUT);
  pinMode(8,OUTPUT);
  pinMode(7,OUTPUT);
}

void loop()
{
  int potValue = analogRead(potPin);
  Serial.println(potValue);
  digitalWrite(13, LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,HIGH);
  delay(potValue);// Wait for 1000 millisecond(s
  digitalWrite(11,LOW);
  digitalWrite(12,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(13,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(potValue);;
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,LOW);
  digitalWrite(10,LOW);
  digitalWrite(8,HIGH);
  digitalWrite(11,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  delay(potValue);https://github.com/kumarkrishna2003/10-days-internship/blob/main/Screenshot%20from%202023-05-18%2011-01-06.png
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(13,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(10,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(12,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(12,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  delay(potValue);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  delay(potValue);
  
  delay(potValue); // Wait for 1000 millisecond(s)
}
```
![alt a1](https://github.com/kumarkrishna2003/10-days-internship/blob/main/Screenshot%20from%202023-05-18%2011-01-06.png)
[thinker this](https://www.tinkercad.com/things/94q0g4u18ho-speed-control-using-pot)
# day 9
[tniker cade](https://www.tinkercad.com/things/9xfCKor8tIz-led-blink-using-switch)
![alt img](
