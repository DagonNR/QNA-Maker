# Uso de Azure QNA Maker, para hacer un Bot de preguntas y respuestas
En este repositorio tenemos una demostración del uso de Azure QNA Maker, para la realización de un Bot, con preguntas y respuestas, además de como vincularlo con Microsoft Teams.

![Microsoft-Azure-QNA-Maker](https://www.outsystems.com/Forge_BL/rest/ComponentThumbnail/GetURL_ComponentThumbnail?ProjectImageId=30779)

---

## Requisitos
- Cuenta en [Microsoft Azure](https://portal.azure.com)
- Un dispositivo, por ejemplo una computadora
- Acceso a internet
- Navegador de internet como Google Chrome, Opera, Mozilla Firefox, etc.

---

## Importante
- Esta práctica se realizó desde [QNA Maker](https://www.qnamaker.ai/)
- Esta práctica utiliza un poco de AI.

---

## Pasos a seguir
- Para empezar debemos entrar [QNA Maker](https://www.qnamaker.ai/).
- Iniciar sesión.
- Iremos al apartado de "Create a knowledge base"
- Ya dentro seguiremos los pasos que nos indiquen.

![P1](https://github.com/DagonNR/QNA-Maker/blob/main/images/P1.PNG)

- El primer paso nos llevará a [Microsoft Azure](https://portal.azure.com), donde crearemos un "QNA Maker"

![P2](https://github.com/DagonNR/QNA-Maker/blob/main/images/P2.PNG)

- Si todo salio bien, nos pondra que se completó la implementación.

![P3](https://github.com/DagonNR/QNA-Maker/blob/main/images/P3.PNG)

- Ya habiendo terminado, regresaremos a completar los pasos, en este caso el segundo, colocaremos nuestra cuenta, suscripción, el QNA Maker que acabamos de crear y un lenguaje.

![P4](https://github.com/DagonNR/QNA-Maker/blob/main/images/P4.PNG)

- Con los pasos terminados ya lo que toca es poner nuestras preguntas y respuestas, estas pueden llevar texto, url, imágenes, gif, etc.

![P5](https://github.com/DagonNR/QNA-Maker/blob/main/images/P5.PNG)

- Ya con las preguntas y respuestas puestas, clicaremos en "Save and train"

![P6](https://github.com/DagonNR/QNA-Maker/blob/main/images/P6.PNG)

- Después iremos al apartado de "Publish" y clicaremos en "Publish".

![P7](https://github.com/DagonNR/QNA-Maker/blob/main/images/P7.PNG)

- Si todo sale bien, nos arrojará el siguiente texto,

![P8](https://github.com/DagonNR/QNA-Maker/blob/main/images/P8.PNG)

- Ahora toca vincular el bot con Microsoft Teams.
- Para esto regresaremos a [Microsoft Azure](https://portal.azure.com).
- Ya dentro buscaremos "Bot Service" y crearemos uno.

![P9](https://github.com/DagonNR/QNA-Maker/blob/main/images/P9.PNG)

- Ya con el recurso creado entraremos en "Canales" y desde aquí podremos vincular nuestro bot, en muchos lugares.
- En este caso para vincularlo con Microsoft Teams, clicaremos en el mismo, y ya dentro lo configuraremos a nuestras necesidades y clicaremos en "Aplicar".

![P10](https://github.com/DagonNR/QNA-Maker/blob/main/images/P10.PNG)

- Y nos arrojará un link para comenzar la conversación con el bot.
