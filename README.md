**Connexions nécessaires :**

1.  **VCC** de l'écran -\> **3.3V** de l'ESP32

2.  **GND** de l'écran -\> **GND** de l'ESP32

3.  **SCL (SCK)** de l'écran -\> **GPIO 18** de l'ESP32

4.  **SDA (MOSI)** de l'écran -\> **GPIO 23** de l'ESP32

5.  **RES (Reset)** de l'écran -\> **GPIO 4** de l'ESP32

6.  **DC (RS)** de l'écran -\> **GPIO 2** de l'ESP32

7.  **CS (Chip Select)** de l'écran -\> **GPIO 5** de l'ESP32

8.  **BLK (Backlight)** de l'écran -\> **3.3V** de l'ESP32 (ou via une résistance si nécessaire)

**Programme Arduino :**

Exemple de programme pour écran TFT 7735 avec ESP32

Click to open Workbench

  - Create tft\_example.ino

**Étapes pour exécuter le programme :**

1.  Installez la bibliothèque Adafruit ST7735 and ST7789 Library via le gestionnaire de bibliothèques Arduino.

2.  Téléversez le programme sur votre ESP32.

3.  L'écran devrait afficher "Bonjour\!" en jaune sur fond bleu, ainsi que des formes géométriques.

Ce programme utilise la bibliothèque Adafruit GFX pour gérer l'affichage sur l'écran TFT. Vous pouvez modifier les couleurs, le texte et les formes selon vos besoins.
