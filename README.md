# python-helpers

## Python 3 Environment Usage / Using VirtualEnv

### Installing VirturalEnv

If it is not already installed, install it using the following command(s):

```
sudo pip install virtualenv
```

### Create Virtual Environment

```
virtualenv -p /usr/bin/python3 venv
```

### Entering the VirtualEnv

```
source venv/bin/activate
```

### Exiting the VirtualEnv

```
deactivate
```

### Creating / Installing Requirements.txt

```
pip3 freeze > requirements.txt
pip3 install -r requirements.txt
```
