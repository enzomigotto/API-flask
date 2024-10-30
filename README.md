import requests
import json
url = 'http://127.0.0.1:5000/matricula'

data = {
    'ra': '9329894',
    'nome': 'João',
    'idade': '16'
}

response = requests.pst(url, json=data)

print('Status Code:', response.status_code)
print('Responde Json:', response.json)# API-flask
Codigo que vai ajudar no ipt ano que vem

------------------------------------------------------------------

import requests
import json
url = 'http://127.0.0.1:5000/matricula'

data = {
    'ra': '9329894',
    'nome': 'João',
    'idade': '16'
}

response = requests.pst(url, json=data)

print('Status Code:', response.status_code)
print('Responde Json:', response.json)
