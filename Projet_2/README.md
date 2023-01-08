J'ai éxécuté le programme en utilisant l'IDE Arduino.

J'ajoute au code projet2nanoble_33 cette partie ci pour faire clignoter la LED 
   if(result.classification[2].value < 0.8) {
    digitalWrite(LED_BUILTIN ,HIGH);
    delay(500);
    digitalWrite(LED_BUILTIN ,LOW);
    delay(400);
    digitalWrite(LED_BUILTIN ,HIGH);
    delay(300);
    digitalWrite(LED_BUILTIN ,LOW);
    delay(200);
    digitalWrite(LED_BUILTIN ,HIGH);
    delay(100);
    digitalWrite(LED_BUILTIN ,LOW);
    delay(50);
   }else {
    digitalWrite(LED_BUILTIN ,LOW);
    
   }
