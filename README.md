# UnisulArduino2023

2. MANIPULANDO UM LED
   
1. void setup()
2. {
3. // Porta 13 (LED_BUILTIN) em modo de saída (escrita)
4. pinMode(LED_BUILTIN, OUTPUT);
5. }
6.
7. void loop()
8. {
9. delay(1000); // Aguarda 1000 milésimos de segundo
10. digitalWrite(LED_BUILTIN, LOW); // Desliga o LED
11. delay(1000); // Aguarda 1000 milésimos de segundo
12. digitalWrite(LED_BUILTIN, HIGH); // Liga o LED
13. }

3. MANIPULANDO 2 LEDS EM SEQUÊNCIA
   
1. int tempo = 0;
2.
3. void setup()
4. {
5. // Porta 13 (LED_BUILTIN) em modo de saída (escrita)
6. pinMode(LED_BUILTIN, OUTPUT);
7. tempo = 1000;
8. }
9.
10. void loop()
11. {
12. delay(tempo); // Aguarda 1000 milésimos de segundo
13. digitalWrite(LED_BUILTIN, LOW); //Desliga o LED
14. delay(tempo); // Aguarda 1000 milésimos de segundo
15. digitalWrite(LED_BUILTIN, HIGH); //Liga o LED
16. }
