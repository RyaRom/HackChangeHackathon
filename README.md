# Инструкция по установке и запуску проекта

## 1. Установка Docker

Скачайте Docker с [официального сайта](https://www.docker.com/products/docker-desktop) и установите его.

---

## 2. Установка Node.js и npm

1. Скачайте и установите Node.js с официального сайта: [https://nodejs.org/](https://nodejs.org/).
   Убедитесь, что вы выбираете LTS-версию.
2. После установки проверьте версии:
    ```bash
    node -v
    npm -v
    ```

## 3. Клонирование репозитория

Клонируйте проект на ваш компьютер:
```bash
git clone https://github.com/RyaRom/HackChangeHackathon
```

## 4. Запуск docker compose
```bash
cd (Папка проекта HackChangeHackathon)

docker-compose up --build
```

## 5. Запуск сайта
1. Отключите CORS в браузере
2. 
```bash
cd (Папка проекта HackChangeHackathon)/frontend/recommendation-module

npm install

npm start
```

## Страница доступна по адресу
```
http://localhost:3000

```
## Swagger UI доступен по адресу

```
http://localhost:8080/swagger-ui/index.html

```
