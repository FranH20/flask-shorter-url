## Aplicacion de acortador de urls

Acortador de URL basico.

`.env` archivo debe contener:

```
SECRET_KEY=verysecretkey
DATABASE_URL=postgresql://<user/>:<password/>@localhost:5432/shortydb
APP_SETTINGS=config.DevelopmentConfig
FLASK_APP=core
```