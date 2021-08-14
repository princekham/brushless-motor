# brushless-motor
https://www.youtube.com/watch?v=IrWBQBgoqf0&t=339s

<H4>Pin Connections</H4>
<H4>Motor 1</H4>
int m1_EL_Start_Stop=5;  //EL  <br>
int m1_Signal_hall=2;   // Signal - Hall sensor . This can be used as external interrupt pin<br>
int m1_ZF_Direction=4;  // ZF <br>
int m1_VR_speed=6;    //VR <br> 

<H4>Motor 2</H4>
int m2_EL_Start_Stop=10;  //EL <br>
int m2_Signal_hall=3;   // Signal - Hall sensor. This will use external interrupt pin <br>
int m2_ZF_Direction=9;  // ZF <br>
int m2_VR_speed=8;    //VR <br>


pinMode(m1_EL_Start_Stop, OUTPUT);//stop/start - EL <br>
pinMode(m1_Signal_hall, INPUT);   //plus       - Signal  <br>
pinMode(m1_ZF_Direction, OUTPUT); //direction  - ZF <br>

pinMode(m2_EL_Start_Stop, OUTPUT);//stop/start - EL <br>
pinMode(m2_Signal_hall, INPUT);   //plus       - Signal  <br>
pinMode(m2_ZF_Direction, OUTPUT); //direction  - ZF <br>
