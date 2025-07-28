# Joke API (The Complete Full‑Stack Web Development Bootcamp)

This is a simple Express‑based REST API for jokes, built as part of the “Complete Full‑Stack Web Development Bootcamp”. It supports CRUD operations, filtering, and protected bulk deletion.

---

## 🚀 Features

1. **GET /random**  
   Returns a single random joke.

2. **GET /jokes/:id**  
   Retrieves the joke with the specified `id`.

3. **GET /filter?type=<type>**  
   Returns all jokes matching the given `type` query parameter.

4. **POST /jokes**  
   Adds a new joke. Expects form data fields:  
   - `text` (string): the joke text  
   - `type` (string): the joke category  

5. **PUT /jokes/:id**  
   Replaces the joke at `id` with the provided `text` and `type`.

6. **PATCH /jokes/:id**  
   Updates one or both fields (`text`, `type`) of the joke at `id`.

7. **DELETE /delete/:id**  
   Deletes the joke at the given `id`.

8. **DELETE /all?key=<masterKey>**  
   Deletes *all* jokes if the correct `masterKey` is provided.
