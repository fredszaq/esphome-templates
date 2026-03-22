# Esphome templates

A set of esphome templates I'm using at home.

## Installation 
```
$ virtualenv -p 3.13 venv # maybe the 3.13 is not required anymore
$ . venv/bin/activate
(venv) $ pip install -r requirements.txt
(venv) $ esphome version # check esphome is properly installed
(venv) $ mv secrets.yaml.template secrets.yaml # then edit with your values
```


## Running on a device
```
(venv) $ esphome run device_config.yaml
```
