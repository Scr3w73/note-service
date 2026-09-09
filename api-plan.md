# API Plan

## Endpoints
- POST   /notes         — создать заметку
- GET    /notes         — получить все заметки
- GET    /notes/{id}    — получить заметку по id
- PUT    /notes/{id}    — обновить заметку
- DELETE /notes/{id}    — удалить заметку
- GET    /notes/search?q=текст — поиск
echo "## API Endpoints

### GET /notes
Получить список всех заметок

### POST /notes
Создать новую заметку

### GET /notes/{id}
Получить заметку по ID

### PUT /notes/{id}
Обновить заметку

### DELETE /notes/{id}
Удалить заметку

### GET /notes/search?q={text}
Поиск заметок по тексту" >> api-plan.md