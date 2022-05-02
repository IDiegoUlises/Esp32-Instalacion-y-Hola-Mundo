# Ch9102 Esp32

<img src="https://github.com/IDiegoUlises/Esp32-Instalacion-y-Hola-Mundo/blob/main/Images/Esp32-Imagen2.jpg" width="500" height="250" />

* **Es un microcontrolador que incorpora conectividad Wifi y Bluetooth**
* **Esta version no necesita presionar el boton para subir el sketch**

### Se debe ir a preferencias y se debe agregar en gestor el siguiente enlace
<img src="https://github.com/IDiegoUlises/Esp32-Instalacion-y-Hola-Mundo/blob/main/Images/Paso1.jpg"/>

* [https://dl.espressif.com/dl/package_esp32_index.json](https://dl.espressif.com/dl/package_esp32_index.json)
* **Luego presionar Ok**

### En gestor de tarjetas se debe buscar esp32 y instalar
<img src="https://github.com/IDiegoUlises/Esp32-Instalacion-y-Hola-Mundo/blob/main/Images/Paso2.jpg"/>

### Por ultimo se debe seleccionar la placa ESP32 Dev Module
<img src="https://github.com/IDiegoUlises/Esp32-Instalacion-y-Hola-Mundo/blob/main/Images/Paso3.jpg"/>

### Apagar y prender el led incorporado en el Esp32
```c++
int led = 2;
void setup()
{
  pinMode(led, OUTPUT);
}

void loop()
{
  digitalWrite(led, HIGH);
  delay(1000);
  digitalWrite(led, LOW);
  delay(1000);
}
```
* **Luego se le da la opcion compilar**
* **Se prendara el led incorporado y se apagara en 1 segundo**
