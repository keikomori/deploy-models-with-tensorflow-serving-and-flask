<h6>This project was developed during the course: </h6>
<h1 align="center">Deploy Models with TensorFlow Serving and Flask</h1>
<h6 align="center">by Coursera Project Network</h6>

Neste projeto foi possível aprender como implantar modelos do TensorFlow utilizando o TensorFlow Serving e Docker, foi criado um aplicativo Web simples com Flask, que serviu como interface para obter as previsões do modelo.

Para executar este projeto é necessário ter o [Docker](https://www.docker.com/) instalado.

O container será criado com o seguinte comando:
```
docker run -p 8501:8501 --name=pets -v "../deploy-models-with-tensorflow-serving-and-flask/pets/:/models/pets/1" -e MODEL_NAME=pets tensorflow/serving
```



<h4 align="center">Tecnologias utilizadas</h4>
<p align="center"> 
  <a href="https://www.python.org" target="_blank"><img src="https://devicons.github.io/devicon/devicon.git/icons/python/python-original.svg" alt="python" width="40" height="40"/></a> 
  <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML" target="_blank"><img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original-wordmark.svg" alt="html" width="40" height="40"/></a> 
  <a href="https://www.docker.com" target="_blank"><img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/></a> 
  <a href="https://flask.palletsprojects.com/en/1.1.x/" target="_blank"><img src="https://www.pngfind.com/pngs/m/104-1044449_python-logo-clipart-drawing-flask-python-hd-png.png" alt="flask" width="40" height="40"/></a> 
</p>
