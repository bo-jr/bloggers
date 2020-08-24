# bloggers

### Learning how microservices work

- 

---

Posts Service

| path   | method | body              | purpose            |   |
|--------|--------|-------------------|--------------------|---|
| /posts | POST   | { title: string } | Create a new post  |   |
| /posts | GET    |                   | Retrieve all posts |   |
|        |        |                   |                    |   |

---

Comments Service

| path                | method | body                | purpose                                             |   |
|---------------------|--------|---------------------|-----------------------------------------------------|---|
| /posts/:id/comments | POST   | { content: string } | Create a comment associated with the given post ID  |   |
| /posts/:id/comments | GET    | -                   | Retrieve all comments associated with given post ID |   |
|                     |        |                     |                                                     |   |
