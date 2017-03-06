# Pixore development

## Getting started

```
git clone https://github.com/development.git pixore-dev && cd pixore-dev
git submodule init && git submodule update
git submodule foreach yarn install
docker-compose up -d
```
And open [http://localhost:8000](http://localhost:8000)

## Add a new submodule

```console
git submodule add https://github.com/pixore/<submodule_name>.git
cd <submodule_name> && yarn install
```