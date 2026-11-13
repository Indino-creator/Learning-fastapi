# Patient Management API (Learning FastAPI)

A simple RESTful API built with **FastAPI** to manage patient records using a local JSON file (`patient.json`) for data storage.

## Features

- **CRUD Operations:** Create, Read, Update, and Delete patient records.
- **JSON Storage:** Lightweight local persistence using `patient.json`.
- **Interactive API Docs:** Automatic documentation powered by Swagger UI and ReDoc.

## Project Structure

```text
├── main.py          # Main FastAPI application and endpoints
├── app.py           # Additional application logic / routes
└── patient.json     # Local JSON database for patient records