# Integrated AI Assistant Architecture

```mermaid
flowchart TD
    A[User Interface] --> B[FastAPI]
    B --> C[Vector Store]
    B --> D[CRM Tool]
    B --> E[PostgreSQL]