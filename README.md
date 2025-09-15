# Go To-Do App

## 🚀 Phase 1: CLI + In-Memory

- A command-line interface that works with an in-memory data store.
- **Focus:** Core features and data models.

---

## 🌐 Phase 2: REST API + JSON Persistence

- Wrap your data store with a RESTful API (**V1**).
- Add JSON-based file persistence.
- Implement context-aware tracing and logging with `context` and `slog`.
- Use Go’s concurrency primitives (`goroutines`, `channels`) to safely support concurrent reads/writes.
- Update the CLI to consume your new API.

---

## 👥 Phase 3: Multi-User Support

- Introduce a **V2 API** that supports multiple users.
- Add a basic **web frontend** for managing tasks.
- Update the CLI to handle multiple users too.
- Validate concurrency safety across users using **parallel tests**.

---

## 🗄️ Phase 4: PostgreSQL Integration

- Add support for **PostgreSQL** as a backend data store.
- Plug it in as an alternative to the JSON file store.
``
