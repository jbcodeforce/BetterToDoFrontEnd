# Better To Do Vue App

Better To Do manages person, project and meeting and add search capability. It was created with

```shell
vue create bettertodoapp
vue add vuetify
```

## Project setup

```shell
yarn install
```

### Compiles and hot-reloads for development

```shell
yarn serve
```

### Compiles and minifies for production

```shell
yarn build
```

### Lints and fixes files

```shell
yarn lint
```

### Dockerize

```shell
# Build
docker build . -t jbcodeforce/bettertodofrontend
# Run
docker run -d -p 8080:80  jbcodeforce/bettertodofrontend
```

## Features

* Support listing persons, meetings and projects
* Add / update new meeting form
* Add / update new person
* Add / update new project