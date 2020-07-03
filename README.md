# Pre-chatbot Simpsons
#### Integrantes: Angulo Rincon Juan Andrés, López Castiblanco Julieth Andrea, Niño Torres Jesus David

<p align="center">
  <img src="https://github.com/JuliethLopez/chatbot_simpsons/blob/master/Imagenes/simpsons.jpg">
</p>

![Éste proyecto](https://www.youtube.com/watch?v=EEAatxHE_1Q&t=12s) se desarrolló durante el semestre 2020-1 en la materia Minería de Datos impartida por el profesor Alvaro Mauricio Montenegro en la Universidad Nacional de Colombia. El objetivo fue desarrollar un chatbot que pudiera responder a un usuario con el estilo de los personajes principales de los Simpsons (Homero, Marge, Lisa y Bart) usando las herramientas vistas que pueden ser consultadas en ![Aprendizaje Profundo.](https://github.com/AprendizajeProfundo/Ciencia-de-Datos)

El chatbot esta compuesto por dos redes, una que clasifica y que está detallada en el cuaderno __Modelo_clasificador_2__ y otra que genera texto y que está detallada en el cuaderno __Generador de texto.ipynb__, se utilizaron dos bases de datos, la base de datos ![The simpsons by the data](https://data.world/data-society/the-simpsons-by-the-data) en el generador de texto y la base de datos ![Dialogue lines of the Simpsons](https://www.kaggle.com/pierremegret/dialogue-lines-of-the-simpsons) en el clasificador, ambas bases de datos se basan en el dataset The Simpsons by the Data hecho por __Tod Schenider__.

Usamos el clasificador para idenficar el estilo al que mas se acerca un usuario con respecto al estilo mismo de los personajes de los Simpsons, para así obtener una respuesta mas certera en la red gerenadora de texto, los modelos se guardaron en drive y se cargaron en el cuaderno __Pre_chatbot.ipynb__ que contiene la función __prechatbot__ que hace todo el proceso utilizando las dos redes.

## Referencias
- ![Imagen de los simpsons, xataca.](https://www.xataka.com/cine-y-tv/simpson-tambien-recuperara-disney-espana-su-formato-original-para-episodios-clasicos)
- ![Aprendizaje Profundo.](https://github.com/AprendizajeProfundo/Ciencia-de-Datos)
