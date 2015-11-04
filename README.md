# App name as ENV to your Dokku app!

Adds app name as an environmental variable to your Docker container run with Dokku. 

Note! Only tested with 0.3.x so far!

## Installation

```
cd /var/lib/dokku/plugins
git clone https://github.com/cjblomqvist/dokku-app-name-env
chmod 755 ./dokku-app-name-env/post-release
```

The environment variable will be set next time you deploy.
