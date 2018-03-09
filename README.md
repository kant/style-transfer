# Transfer Style - Sample App in Python

## Getting started

### Local run

1. Modify files in local_vcaps to contain vcaps of your services.

Run:
```bash
python server.py
```

Then, application is available at `127.0.0.1:8080`


### Bluemix run

1. Modify `manifest.yml` as you wish.
2. Run:
   ```bash
   cf api <API-endpoint>
   cf login
   cf push
   cf apps
   ```