# Braco-Robotico-
Códigos do projeto de arduino (braço robótico) | 1º ano, técnico em informática, 20
Código teste arduino:
//Projeto arduino piscar led


void setup() { 
    pinMode(8, OUTPUT);
    pinMode(9, OUTPUT);
    pinMode(10, OUTPUT);
    
    
}

void loop(){ 
    //Controle led verde 
  digitalWrite(10,HIGH); //acende led
  delay(300);    //espera
  digitalWrite(10,LOW); //apaga

  //controle led amarela
   digitalWrite(9,HIGH); //acende led
  delay(200);    //espera
  digitalWrite(9,LOW); //apaga

  //controle led vermelha
   digitalWrite(8,HIGH); //acende led
  delay(300);    //espera
  digitalWrite(8 ,LOW); //apaga

}
