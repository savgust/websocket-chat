# 🧠 Go WebSocket ChatApp

Простой чат-приложение на Go, использующее WebSocket для обмена сообщениями в реальном времени. Это минимальный пример сервера и клиента с HTML-интерфейсом.

## 🚀 Функциональность

- Обмен сообщениями в браузере (эхо-сервер)
- Использует `gorilla/websocket`
- Интерфейс на HTML + jQuery
- Простая архитектура: `main.go`, `room.go`, `client.go`, `chat.html`

---

## 🛠️ Установка и запуск

### 1. Установите [Go](https://go.dev/dl/)

Убедитесь, что Go установлен:

```bash
go version

git clone https://github.com/EsotericTech/chatapp.git
cd chatapp

go mod tidy

go run main.go room.go client.go

go build
./chatapp
