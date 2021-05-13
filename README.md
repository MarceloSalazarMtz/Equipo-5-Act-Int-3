# Equipo 5 Actividad Integradora 3
---
## ¿Qué hace este proyecto?
Este proyecto se realizó utilizando la técnica de web data scrapping para recolectar imágenes de una base de datos en línea. La base de datos que se utilizó es shutterstock.com, la cual está enfocada a datos en forma de imagen. El programa solicitará una al usuario un término para buscar en la base de datos y posteriormente el número de fotos que se quieren obtener. Posteriormente, el programa almacenará las imágenes obtenidas en tres folders llamados train, validation y test, en donde se enviaran el 80%, 13% y 7% de la totalidad de las imágenes encontradas, respectivamente. Dentro de los tres forlder, se crean 5 categorias llamadas: hot dogs, pizza, salad, spaguetti y tacos. Al buscar las imagenes, estas son distribuidas en su respectivo folder que servian para etrenar, validar y probar el modelo predictivo. Para el entrenmiento del modelo de prediccion de imagenes, se utilizo la tecnica de transfer learning, en donde se utiliza un modelo previamente entrenado para transferir su conocimiento a un modelo diferente pero similar. Por ultimo se probaron distintas configuraicones, utilizando diferentes epochs y congelando distintos paramentras para obtener el modelo mas precisio. Al final, se obtuvo que el modelo que predice la categoria de las imagenes de mejor manera, es con una configuracion de 20,000 parametros y 8 epochs, obteniendo un 80% de precision. 
## ¿Por qué es útil este proyecto?
Este proyecto ayuda a los usuarios a entrar en contacto con el mundo de la visión por computadora por medio de algoritmos que nos solicitan términos de entrada y en base a ellos nos arrojan imágenes obtenidas de una base de datos para posteriormente ser clasificadas. Esto es muy util porque nos brinda conocimiento y herramientas que pueden ser de gran utilidad en un sinfin de aplicaciones al realizar la clasificacion de imagenes por medio de algoritmos y modelos de machine learning. Por otro lado, nos ayuda a la diversificación de imágenes en distintos folders para poder obtener información de prueba e información de entrenamiento para algún modelo determinado, en caso de ser requerido.
## ¿Cómo pueden los usuarios usar este proyecto?
Es posible utilizar este proyecto para obtener imágenes de una base de datos a través del modelo programado en el archivo de la jupyter notebook creada por el equipo 5 de la clase de computer vision. Dentro de este archivo se encuentra el codigo utilizado para la relizacion de todo lo anteriormente descrito, asi como comentarios importantes que pueden guiar a los usuarios en su implementacion.
## ¿En dónde pueden los usuarios conseguir ayuda con respecto a nuestro proyecto?
Cualquier duda respecto al proyecto o al modelo en sí, puede ser solucionada contactando a cualquier miembro del equipo 5.
## ¿Quién mantiene y contribuye a este proyecto?
Este proyecto es mantenido por todos los contribuyentes en su desarrollo, pertenecientes al equipo 5 de computer vision, que son los siguientes:

-Francisco Ismael Sainz Williams

-Marcelo Alejandro Salazar Martínez

-Marcelo Suarez Ponce

-Arturo Vázquez Muñoz


