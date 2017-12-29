<p align="center">
  <img src="http://i.imgur.com/k8I15Gh.png" alt="Trinity 3"/>
</p>
====
[![PEP8](https://img.shields.io/badge/code%20style-pep8-orange.svg)](https://www.python.org/dev/peps/pep-0008/)

*WIP*

How to setup
-------------------
- Install Python 3+
https://www.python.org/

- Install MySQL Server
https://www.apachefriends.org/index.html

- Configure `config.ini`

--------------------
Run the command below to install required modules. (pip or pip3)

```sh
pip3 install -r requirements.txt
```

How to run
----------------
#### Local / development environment
```sh
python3 trinity_server.py
```
###### Windows users can simply launch `win_launch.bat`
--------------------

#### Gunicorn production environment
```sh
gunicorn3 -k geventwebsocket.gunicorn.workers.GeventWebSocketWorker -w 1 Core:app
```
#### Passenver production environment
- See `passenger_wsgi.py`
----------------

<br /><br />


## Screenshots
![Alt Text](http://image.prntscr.com/image/8c36a0e9d5eb4c3aa23806032e39f341.png)
![Alt Text](http://image.prntscr.com/image/019c80da5c47430d957787dcfeb3fc01.png)
![Alt Text](http://image.prntscr.com/image/e6951df674ed496b827154942bc91f08.png)
![Alt Text](http://image.prntscr.com/image/52f4fd5e66e74fcaad8fe50ca54ae043.png)
![Alt Text](http://image.prntscr.com/image/4ae0d358e96f4048a117dd73f58c4588.png)