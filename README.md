# Codecrafthubpush
## Project Overview
CodeCraftHub is a personal learning goal tracker API designed for developers. It allows users to manage their learning courses by tracking course details such as name, description, target completion date, and current status. This project serves as a practical example of building a REST API using Node.js and Express.

## Features
- Create, read, update, and delete (CRUD) courses.
- Each course includes:
  - ID (auto-generated)
  - Name (required)
  - Description (required)
  - Target completion date (required, format: YYYY-MM-DD)
  - Status (required, must be: "Not Started", "In Progress", or "Completed")
  - Created timestamp (auto-generated)
- Simple JSON file storage for course data.
## Installation Instructions
1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd codecrafthub
