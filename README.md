# IOT
#define vermelho_1 8
#define amarelo_1 9
#define verde_1 10

#define vermelho_2 5
#define amarelo_2 6
#define verde_2 7

 
void setup()
{
  pinMode(vermelho_1, OUTPUT);
  pinMode(amarelo_1, OUTPUT);
  pinMode(verde_1, OUTPUT);
  
  pinMode(vermelho_2, OUTPUT);
  pinMode(amarelo_2, OUTPUT);
  pinMode(verde_2, OUTPUT);
 
}

void loop()
{
   

  digitalWrite(vermelho_1, HIGH);
  digitalWrite(vermelho_2, HIGH);
  delay(1000);

  digitalWrite(vermelho_1, LOW);
  digitalWrite(verde_1, HIGH);
  delay(3000);

  digitalWrite(verde_1, LOW);
  digitalWrite(amarelo_1, HIGH);
  delay(1000);

  digitalWrite(amarelo_1, LOW);
  digitalWrite(vermelho_1, HIGH);
  delay(1000);

  digitalWrite(vermelho_2, LOW);
  digitalWrite(verde_2, HIGH);
  delay(3000);

  digitalWrite(amarelo_2, HIGH);
  digitalWrite(verde_2, LOW);
  delay(1000);
  
  digitalWrite(amarelo_2, LOW);
  
}
 
 
