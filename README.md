# Go Micro Template

This is a template for a microservice written in Go.

## Overview

You can start your microservice applications that you will develop with Go without any architectural concerns. This template is for illustrative purposes only. Technologies used may vary. This template has been developed in a way that does not hinder most Technologies.

## Project Structure

```
📦microservice-app
┣ 📂src
┃ ┣ 📂app
┃ ┃ ┗ 📜app.go
┃ ┣ 📂config
┃ ┃ ┗ 📜config.go
┃ ┣ 📂dto
┃ ┃ ┣ 📜some_create.go
┃ ┃ ┣ 📜some_created.go
┃ ┃ ┣ 📜some_find.go
┃ ┃ ┗ 📜some_found.go
┃ ┣ 📂entity
┃ ┃ ┗ 📜some.go
┃ ┣ 📂event
┃ ┃ ┣ 📜some_created.go
┃ ┃ ┗ 📜some_deleted.go
┃ ┃ ┗ 📜some_feature_created.go
┃ ┣ 📂event_handler
┃ ┃ ┣ 📜event_handler.go
┃ ┃ ┗ 📜some_feature_created.go
┃ ┣ 📂event_publisher
┃ ┃ ┣ 📜event_publisher.go
┃ ┃ ┣ 📜some_created.go
┃ ┃ ┗ 📜some_deleted.go
┃ ┣ 📂internal
┃ ┃ ┣ 📜api.go
┃ ┃ ┣ 📜handler.go
┃ ┃ ┣ 📜repo.go
┃ ┃ ┗ 📜service.go
┃ ┣ 📂locales
┃ ┃ ┣ 📜en.toml
┃ ┃ ┗ 📜tr.toml
┃ ┣ 📂mapper
┃ ┃ ┣ 📜mapper.go
┃ ┃ ┗ 📜some_mapper.go
┃ ┣ 📜app.env
┃ ┗ 📜main.go
┣ 📜.gitignore
┣ 📜Dockerfile
┣ 📜go.mod
┗ 📜go.sum
```

## Folder Descriptions

In this repository, there is a `README.md` file under each folder, and in this file, what the folder does is explained in detail. For example, [you may want to visit the `src` folder.](https://github.com/ssibrahimbas/go-micro-template/tree/main/src)

### License

[MIT](https://choosealicense.com/licenses/mit/)

### Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.


### Authors

- [Sami Salih İbrahimbaş](https://github.com/ssibrahimbas)