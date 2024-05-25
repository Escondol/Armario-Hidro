<div align="center">
  <h1 align="center">Armario Hidropónico</h1>
  <img height="450px" src="https://github.com/Escondol/Armario-Hidro/assets/86692164/91512669-405f-489a-8807-8430636d0057" alt="4Ponic">
</div>

## Descripción del proyecto
La hidroponía interior es una forma de cultivar plantas sin suelo, ya sea sumergiendo sus raíces en un recipiente de agua mezclada con nutrientes o suspendiéndolas en fibras sobre un depósito igualmente enriquecido. "Hidroponía" proviene de la palabra griega "hydro", que significa agua, y "ponos", que significa trabajo. En este proyecto se ha diseñado e implementado un sistema hidropónico interior (indoor) NFT que permite un control integral de variables como el pH, la conductividad eléctrica, la cantidad de luz y otros factores ambientales, con el fin de optimizar el crecimiento y rendimiento de los cultivos de lechugas.

## Diseño
### Estructura
Este armario ha sido realizado desde cero, desde la estructura hasta el tanque que almacena el agua:
- Para realizar las tuberías, el tanque y la caja del circuito electrónico, hemos utilizado un material denominado **Sintra**.
- Para construir la estructura, hemos **reciclado** palos de **madera** y una plancha de **hidrófugo**.
- Para la sujeción de la tubería con la base, hemos cortado tiras de **aluminio** y las hemos ajustado con **tornillos** a la base.
<div align="center">
  <img height="250px" src="https://github.com/Escondol/Armario-Hidro/assets/86692164/a3a69483-d191-4957-ac19-2888daf92d7b" alt="Tuberia 1">
  <img height="250px" src="https://github.com/Escondol/Armario-Hidro/assets/86692164/da884a63-3a08-482b-9cb0-b75b422b9211" alt="Tuberia 2">
</div>


### Electrónica
Para controlar todo el sistema, hemos utilizado un ESP32 C3. Este se encarga de monitorear las condiciones del invernadero, como el pH del agua, la temperatura, la humedad y la conductividad eléctrica, y de activar o desactivar los diferentes actuadores que controlan el encendido o apagado de la bomba, las luces y los abanicos.

El sistema también cuenta con una aplicación móvil que ha recibido los datos enviados por el ESP32 sobre el estado actual del sistema. Además, hemos integrado una pantalla OLED para desplegar estos valores.
<div align="center">
<img height="350px" src="https://github.com/Escondol/Armario-Hidro/assets/86692164/8a24f5f5-f464-47c2-bbc3-7cf6c55624c8" alt="Diagrama de Bloque">
</div>

## Técnologías Utilizadas
- Electrónica
- Software de Diseño PCB (KiCAD)
- Software de Dibujo (Fusion 360)
- Simulador (Multisim)
- Aplicación Móvil (MIT App Inventor) 

## Creditos y Contactos
- Contreras, Dojanni E.; esmerling.contreras@gmail.com
- Contreras, Sheila; sheilacontr23@gmail.com
- Montilla, Oscar A.; montillaoscar6@gmail.com
- Liriano, Gabriela M.; lirianotejedagabrielamargarita@gmail.com
- Ramírez, Nelson J.; eduard8219@hotmail.com
- Segura, Angel G.; angelgabrir23@gmail.com

## Anexos y Funcionamiento
<div align="center">
  <h3>Día 1</h3>
  <img height="350px" src="https://github.com/Escondol/Armario-Hidro/assets/86692164/e4ef0fb0-9743-4205-8986-c5cb31a104b4" alt="Día 1 Lechugas">
  <h3>Día 14</h3>
  <img height="350px" src="https://github.com/Escondol/Armario-Hidro/assets/86692164/c30b4df0-b6a4-4fa8-8cad-9105f481dacd" alt="Día 14 Lechugas">
  <h3>Día 30</h3>
  <img height="350px" src="https://github.com/Escondol/Armario-Hidro/assets/86692164/2c6ef793-bf73-4bbf-8e8a-d35b5c93840f" alt="Día 30 Lechugas">
  <p><strong>PD: La primera lechuga de izquierda a derecha fue reemplazada</strong></p>
</div>

