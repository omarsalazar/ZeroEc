# ZeroEc
Future e commerce. Hopefully it could be used as my own portfolio as well.

### Guía de instalación.

#### Clona el proyecto.
```
git clone https://github.com/omarsalazar/ZeroEc
cd ZeroEc
```

#### Entorno virtual

Instalación del entorno.
```
pip install python-virtualenv
```
Creación del entorno virtual.
```
virtualenv -p python3 myvenv
```
Activación.
```
source myvenv/bin/activate
```

#### Instalación de dependencias.
```
pip install -r requirements.txt
```
### Ejecuta el proyecto.
```
python manage.py migrate
python manage.py runserver 0.0.0.0:8000
```

