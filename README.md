## Django bootstrap project template
### Includes
* twitter bootstrap
* django-annoying
* django-compressor

### How to use
Create virtual environment, change project_name with your projects name :D
```
mkvirtualenv project_name
```
Install requirements
```
pip install -r requirements.txt
```
Run django startproject with the --template option
```
django-admin.py startproject --template=https://github.com/netoxico/django-bootstrap/archive/master.zip project_name
```