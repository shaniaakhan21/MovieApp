## Initial Setup Instructions

### Setup Python Virtual Environment
```buildoutcfg
python3 -m venv venv
. venv/bin/activate
pip3 install -r requirements.txt
```
## Running Server

```buildoutcfg
./mange.py migrate
./mange.py runserver
```
### Go and check `http://127.0.0.1:8000/`
