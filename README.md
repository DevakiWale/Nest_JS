
markdown
# NestJS

This is the source code for the **Nest.js** 


## 🧠 What You'll Learn

This project covers all the fundamental concepts of building a REST API using NestJS, including:

- 🏗️ NestJS CLI and project structure
- 📦 Modules, Controllers, and Services
- 📥 Dependency Injection
- 📃 DTOs (Data Transfer Objects)
- ✅ Validation using `class-validator`
- 🧑‍💼 Role-based Access Control
- 🗃️ PostgreSQL with Prisma ORM
- 🧪 CRUD APIs for Users and Posts
- 🔐 Protected Routes with Guards

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or later)
- npm / yarn
- PostgreSQL (you can use [Neon.tech](https://neon.tech/) or install locally)
- NestJS CLI (optional for development)

```bash
npm install -g @nestjs/cli
````

### Installation

1. Clone the repo:

```bash
git clone https://github.com/yourusername/nestjs-course.git
cd nestjs-course
```

2. Install dependencies:

```bash
npm install
```

3. Create `.env` file:

```env
DATABASE_URL="postgresql://user:password@localhost:5432/yourdbname"
```

4. Run Prisma migration:

```bash
npx prisma migrate dev --name init
```

5. Generate Prisma client:

```bash
npx prisma generate
```

---

## 🛠️ Run the App

### In Development:

```bash
npm run start:dev
```

### In Production:

```bash
npm run build
npm run start:prod
```

---

## 🧪 API Endpoints

### Users

* `GET /api/employees`
* `GET /api/employees/:id`
* `PATCH /api/employees/:id`
* `DELETE /api/employeesgit init
/:id`

### Protected Routes

Use the JWT token in headers:

```http```


## 🗂️ Folder Structure

```bash
src/
├── database/
├── employees/
├── my-logger/
├── users/
├── main.ts
├── app.module.ts
```

---

## 📦 Tech Stack

* NestJS
* Prisma ORM
* PostgreSQL
* class-validator (Validation)
---
=======
# Nest_JS

