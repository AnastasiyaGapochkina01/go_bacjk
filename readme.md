```
.
├── backend
│   ├── Dockerfile
│   ├── go.mod
│   ├── go.sum
│   └── main.go
├── db
│   └── password.txt
├── compose.yaml
├── proxy
│   └── nginx.conf
```
В проекте есть приложение на go (слушает на 8000 порту), БД postgres, и nginx как прокси

В папке db есть файл password.txt - его надо использовать как secret в compose (https://docs.docker.com/compose/use-secrets/) - это вариант когда мы не используем .env файлы



