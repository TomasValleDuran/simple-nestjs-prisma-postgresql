# NestJS Prisma PostgreSQL Template

## Overview

This repository serves as a **starter template** for building applications with:
- **NestJS** - Progressive Node.js framework for building scalable server-side applications
- **Prisma** - Type-safe database ORM and query builder
- **PostgreSQL** - Robust relational database

## Purpose

This template is designed to:
- 🚀 **Get you started quickly** with a fully configured NestJS + Prisma + PostgreSQL stack
- ☁️ **Test cloud deployments** - Ready for deployment to platforms like Heroku, Railway, Vercel, AWS, etc.
- 📚 **Learn best practices** - Includes proper project structure, validation, error handling, and type safety
- 🧪 **Prototype rapidly** - Complete CRUD operations out of the box

## What's Included

- ✅ Complete **User CRUD API** with validation
- ✅ **Prisma** integration with PostgreSQL
- ✅ **DTO validation** using class-validator
- ✅ **Global error handling**
- ✅ **TypeScript** configuration
- ✅ **ESLint & Prettier** setup
- ✅ **Docker Compose** for local PostgreSQL

## Quick Start

1. **Clone and install dependencies:**
   ```bash
   npm install
   ```

2. **Set up your database:**
   - Start PostgreSQL with Docker: `docker-compose up -d`
   - Or configure your own PostgreSQL instance in `.env`

3. **Configure environment:**
   ```bash
   # Create .env file
   DATABASE_URL="postgresql://username:password@localhost:5432/nestjs_prisma_db?schema=public"
   PORT=3000
   ```

4. **Initialize database:**
   ```bash
   npx prisma generate
   npx prisma db push
   ```

5. **Start development server:**
   ```bash
   npm run start:dev
   ```

## API Endpoints

- `POST /user` - Create user
- `GET /user` - Get all users
- `GET /user/:id` - Get user by ID
- `PATCH /user/:id` - Update user
- `DELETE /user/:id` - Delete user

## Cloud Deployment Ready

This template is optimized for cloud deployment with:
- Environment variable configuration
- Production build scripts
- Proper error handling
- Database connection management

Perfect for testing on platforms like **Heroku**, **Railway**, **Render**, **Vercel**, or **AWS**.

---

*Feel free to use this template as a starting point for your NestJS projects!*
