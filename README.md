# Clicker---Rect-Native

Tipico juego estilo clicker hecho en React Native

![imagen](https://github.com/user-attachments/assets/e2731a7f-1b0c-401e-b9de-f33d0d7361c6)

Cada elemento tiene una funcionalidad:
  - El sol modifica el contador en función de los efectos de las nubes que estén activos ( de manera predeterminada suma 1 )
  - La nube oscura resetea todo y vuelve el contador a 0
  - La nube con una estela de arco iris hace que el contador sume de 10 en 10
  - Las dos nubes que unen un arco iris restan 5 al contador
  - La luna hace que el contador sume o reste el valor actual del sol
  - Y la nube que sopla hace que automaticamente se sume 1 al contador cada medio segundo.

![imagen](https://github.com/user-attachments/assets/47ed06ab-0f8c-46d5-bcf2-ff9531c6b729)

Solo puedes tener una nube activa a la vez, salvo la que sopla, la nube que está activa pierde un poco de opacidad. Puedes volver a pinchar en la nube 
para desactivar su efecto. Si tienes una nube activa y pulsas otra, se desactiva la anterior automáticamente.
