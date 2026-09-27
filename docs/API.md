# To-do API

The server listens on **port 3000**.

| Method | Path | Purpose |
| --- | --- | --- |
| GET | /items | List all to-dos |
| POST | /items | Create a to-do |
| PUT | /items/:id | Update a to-do |
| DELETE | /items/:id | Delete a to-do |

Set `SQLITE_DB_LOCATION` to choose where the SQLite file is stored (defaults to `/etc/todos/todo.db`). Alternatively, set `MYSQL_HOST` to use MySQL instead of SQLite.