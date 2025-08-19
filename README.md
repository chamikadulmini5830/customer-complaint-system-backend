# Customer Complaint System — Backend

A Node.js + Express REST API with MongoDB for managing customer complaints.

## Endpoints (CRUD)
- `GET /complaints` — List complaints (query: `status`, `priority`, `q` for search)
- `GET /complaints/:id` — Get a complaint
- `POST /complaints` — Create complaint
- `PUT /complaints/:id` — Update complaint
- `DELETE /complaints/:id` — Delete complaint

## Run Locally
1. `npm i`
2. Create `.env`:
