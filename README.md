
```shell
sudo apt install python3-pip -y
sudo apt install virtualenv -y
```

```shell
which python3 

virtualenv venv3 -p python3

source venv3/bin/activate

easy_install distribute

cd django-jenkins

pip install -r requirements.txt

pip freeze

make lmigrate 

make developmentrun
```