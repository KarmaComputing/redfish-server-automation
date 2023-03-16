# Control Physical Server(s) via the Redfish api (e.g. Dell iDRAC)

[Redfish-boot-server-python-api-idrac-2023-03-16 20-48-51.webm](https://user-images.githubusercontent.com/1718624/225755339-faafd339-4d5f-4d12-b7a7-8187d7963362.webm)

Associated blog post: [DevOps with physical servers using Redfish Python api](https://blog.karmacomputing.co.uk/devops-with-physical-servers-redfish-python-api-idrac/)

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

