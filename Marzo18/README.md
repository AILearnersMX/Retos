# Clasificación de género de canciones

**¡Bienvenidos y bienvenidas al reto de Marzo!** 

En este reto, podrás clasificar canciones según su género a partir de cosas como el año y la letra de la canción. Este es un problema de clasificación. El problema está diseñado para ser abierto y para que puedas explorar diferentes soluciones. Utilizaremos Python. 

En el archivo  `Problema.ipynb` explicamos cómo importar el archivo csv utilizando una librería llamada Pandas. También cargamos el dataset y lo barajamos. Finalmente, separamos el dataset en training, testing y validation. 

## ¿Cómo resolverlo?
¡Este problema es para gente de todos los niveles! Puedes proponer la solución que quieras. En este caso, como ya tenemos las características a partir de las cuáles queremos predecir, es un ejemplo de aprendizaje supervisado. 

Te sugerimos revisar [scikit-learn](http://scikit-learn.org/stable/supervised_learning.html). Esta es una librería de Python que viene con implementaciones de diferentes técnicas con las que podrías resolver este problema.  No es necesario utilizar `scikit-learn`, puedes tomar las decisiones que tú quieras. 

Una vez que tengas el reto resuelto con una precisión que consideres adecuada, [escríbenos un mensaje en Facebook](https://www.facebook.com/AILearners/).

## Tips para principiantes

Es normal no lograr una solución inmediatamente. Lo mejor es empezar entendiendo la información.

1. **Entender y procesar la información**
Revisa la información. Mira los posibles valores en cada columna (feature). ¿Qué problemas hay? Es probable que debas quitar algunos registros que han sido cargados por no tener suficiente información. Otra posibilidad es que tengas que hacer un proceso llamado [one hot encoding](https://hackernoon.com/what-is-one-hot-encoding-why-and-when-do-you-have-to-use-it-e3c6186d008f). Sin importar cómo decidas resolver este problema, es esencial que primero entiendas lo que tienes. No digas "quiero resolver esto con redes neuronales" sin antes entender si es algo que se puede solucionar con ellas.

2. **Proponer una solución**
Al proponer una solución, te sugerimos iniciar intentando algo sencillo. Un modelo básico, que puedas implementar en poco tiempo, para poder medir su desempeño base. A partir de tener un desempeño mínimo, ya tendrás un punto de comparación. No hay una manera correcta de solucionar este problema: hay muchos enfoques válidos diferentes.

**¡Éxito!**
