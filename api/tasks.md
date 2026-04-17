# Tasks API

This endpoint allows you to retrieve and create tasks.

---

## 📍 Endpoints

### Get Tasks

```http
GET /tasks

curl -X GET "https://api.taskflow.com/tasks?page=1&limit=10" \
  -H "Authorization: Bearer YOUR_API_KEY"
