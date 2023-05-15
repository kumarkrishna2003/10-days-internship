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
- 7 segament display using arduino
[thinker this](https://www.tinkercad.com/things/f5GIdlII1CW-7-segament-display-using-arduino-board)
