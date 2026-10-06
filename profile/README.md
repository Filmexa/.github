# 🎬 Filmexa

**Filmexa** is a full-stack movie discovery and streaming platform developed as part of the **42 Hypertube project**.

The platform combines movie discovery, torrent-based downloading, real-time streaming, adaptive video playback, and user management in a single application.

## ✨ Key Features

- 🔐 Secure authentication with JWT, refresh-token cookies, BCrypt, email verification, password recovery, and rate limiting
- 🌐 OAuth authentication with 42, Google, and Facebook
- 🎞️ Movie discovery, search, filtering, categories, trailers, and watchlists
- ⚡ Background torrent downloads with progress tracking
- 📺 Adaptive HLS streaming with multiple quality levels
- 🔄 On-the-fly video transcoding with FFmpeg
- 💬 Movie comments and user profiles
- 🌍 Internationalization in English, French, and Arabic
- 🧹 Automatic cleanup of inactive movie files
- 📖 REST API documentation with OpenAPI / Swagger
- 🧪 Unit and integration testing
- 🐳 Docker Compose environment for frontend, backend, and PostgreSQL

## 🛠️ Tech Stack

**Frontend**
- Angular 19
- TypeScript
- HLS.js

**Backend**
- Java 17
- Spring Boot
- Spring Security
- Spring Data JPA

**Infrastructure & Media**
- PostgreSQL
- FFmpeg
- Docker
- Docker Compose

**External Services**
- TMDB
- External torrent providers

## 🚀 Streaming Architecture

One of the main technical challenges of Filmexa was enabling playback while movie content was still being downloaded.

The application handles downloading, buffering, transcoding, HLS playlist generation, concurrency, and error recovery so that media can be prepared and streamed without blocking the rest of the system.

## 👥 Team

Filmexa was developed collaboratively by:

- **Marouane Addou**
- **Mohamed Baanni**
- **Mohssen El Gandali**
- **Karim Chaouki**

## 📌 Project Management

We used **GitHub Projects** to organize the development workflow across:


---

Built with passion as part of the **42 Hypertube project**. 🚀
