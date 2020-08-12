# profiles-rest-api
Source code for profiles REST API course


Erro:

```WARNING: Retrying (Retry(total=4, connect=None, read=None, redirect=None, status=None)) after connection broken by 'NewConnectionError('<pip._vendor.urllib3.connection.HTTPSConnection object at 0x7fe314dbdf50>: Failed to establish a new connection: [Errno -3] Try again')': /simple/django/```

Solução:

```firewall-cmd --permanent --zone=trusted --add-interface=docker0```

```firewall-cmd --reload```
