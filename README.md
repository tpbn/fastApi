## API Endpoints

RESTful API endpoints for managing the book records:

| Method | Endpoint   | Description            |
|--------|------------|------------------------|
| GET    | `/books`   | Fetch all books        |
| POST   | `/books`   | Add a new book         |

---

- **Base URL:** `https://fastapi-lwt8.onrender.com`
- **Swagger Docs:** `https://fastapi-lwt8.onrender.com/docs`

---

###  Request Payload (for POST)

```json
{
  "title": "Book Title",
  "author": "Author Name"
}
