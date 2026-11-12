# Learnly

## go live

Install Node.js 18 or newer, then run:

```sh
npm start
```

Open Enrollments and notes are stored in `data/store.json` and remain available after restarting the server. Use `PORT` to choose another port.

The backend exposes `GET /api/courses`, `GET` and `POST /api/enrollments`, and `GET`, `POST`, and `DELETE /api/notes`. This starter site has no account or sign-in system, so its local data is shared by anyone who can access the running server; it is not suitable for private multi-user deployment.

Run the backend tests with `npm test`.
