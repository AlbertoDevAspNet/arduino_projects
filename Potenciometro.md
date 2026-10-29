int LED = 3;
int brilho;
void setup() {
  // put your setup code here, to run once:
  pinMode(LED, OUTPUT);

}

void loop() {
  // put your main code here, to run repeatedly:
  for(brilho = 255; brilho  >= 0; brilho--){
    analogWrite(LED, brilho);
    delay(15);
  }

}
