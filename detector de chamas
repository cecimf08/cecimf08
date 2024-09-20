const int LED = 13;           // Define o pino para o LED
const int Flame_sensor = 2;   // Define o pino para o sensor de chama

void setup() {
  pinMode(LED, OUTPUT);        // Configura o pino do LED como saída
  pinMode(Flame_sensor, INPUT); // Configura o pino do sensor de chama como entrada
}

void loop() {
  int Flame_detected = digitalRead(Flame_sensor); // Lê o valor do sensor de chama

  if (Flame_detected == 1) {  // Verifica se a chama foi detectada
    digitalWrite(LED, HIGH);   // Acende o LED
  } else {
    digitalWrite(LED, LOW);    // Apaga o LED
  }
}
