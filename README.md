# Control Physical Server(s) via the Redfish api (e.g. Dell iDRAC)


## Setup

```
git clone git@github.com:KarmaComputing/redfish-server-automation.git
cd redfish-server-automation
git clone https://github.com/dell/iDRAC-Redfish-Scripting.git iDRAC-Redfish-Scripting/ #TODO submodule
```

## Install

```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Run

```
flask run --debug
```

Visit http://127.0.0.1:5000

Control your server!

> Note the default config in `app.py`

