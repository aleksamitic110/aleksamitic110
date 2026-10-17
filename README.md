# Aleksa Mitić

Software developer from Niš, Serbia, focused on backend development with C# and .NET.

I hold a BSc in Computer Science and Informatics from the Faculty of Electronic Engineering, University of Niš, and I'm starting my Master's studies. I like building APIs that are tested, containerized, and documented well enough that someone else can run them on the first try.

I'm open to **internships and junior developer roles**.

## Projects

### [SecureExamIDE](https://github.com/aleksamitic110/SecureExamIDE) · in progress

A system for taking programming exams on students' own laptops, fully offline on exam day. Exam packages are encrypted and downloaded in advance, then unlocked in the room with a one-time code that the server never stores. Laptops authenticate with per-device keys instead of passwords, and each submission is sealed and fingerprinted so it can't be changed after hand-in.

- **Status:** the ASP.NET Core Web API is mostly complete (registration, exam publishing, encrypted packages, submissions); the Avalonia desktop client is still at an early stage.
- **Stack:** .NET 10, ASP.NET Core, PostgreSQL, MinIO, Docker, Avalonia

### [Calendar Tasking API](https://github.com/aleksamitic110/Calendar-Tasking)

A REST API for calendars, events, tasks, and tracking private tutoring sessions and payments, built for a software quality assurance course. The focus is on testing: NUnit component tests run against an in-memory API host, and Playwright tests cover the API and UI flows. The whole stack, with its database schema and seed data, starts with a single Docker Compose command.

- **Stack:** .NET 9, ASP.NET Core, Entity Framework Core, SQL Server, NUnit, Playwright, Docker

### [Advanced Video Search](https://github.com/aleksamitic110/Advanced-video-search)

An information retrieval project that indexes YouTube videos and searches them by text, by image, and by visual description. A Spring Boot backend handles Lucene full-text search, frame extraction, and vector search in PostgreSQL with pgvector, while a separate Python service generates CLIP embeddings.

- **Stack:** Java 21, Spring Boot, Apache Lucene, PostgreSQL + pgvector, Python (FastAPI), Docker

### Smaller projects

- [PDF Catalog Order Manager](https://github.com/aleksamitic110/PDF_Catalog-to-Interactive_page): Python desktop app that parses product catalogs from PDF and exports orders to Excel/PDF (PySide6, PyMuPDF, PyInstaller build on GitHub Actions)
- [ZI_Cryptography](https://github.com/aleksamitic110/ZI_Cryptography): Windows Forms app with hand-written RC6, PCBC mode, Playfair, and SHA-1, plus encrypted file transfer over TCP
- [JKP-Obavestenja](https://github.com/aleksamitic110/JKP-Obavestenja): scheduled Python job on GitHub Actions that emails alerts about water outages in selected streets

## Experience

- **Programming tutoring:** private lessons for students in programming and computer science courses
- **Freelance development:** software projects for individual clients

## Technologies

- **Main:** C#, .NET / ASP.NET Core, Entity Framework Core, SQL (PostgreSQL, SQL Server), Python, Docker, Git
- **Also worked with:** Java / Spring Boot, Kotlin / Jetpack Compose, TypeScript, NUnit, Playwright
