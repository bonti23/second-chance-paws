# Second Chance Paws 🐾

Aplicație web pentru adopția animalelor fără stăpân și sprijinirea centrelor care le adăpostesc.
Proiect personal, cu date demonstrative fictive.

## Tehnologii
- Java 21, Spring Boot 4.1, Hibernate, Spring Security (JWT)
- PostgreSQL 17 + Flyway
- React + TypeScript, Leaflet / OpenStreetMap
- Claude API (asistent AI)
- Docker & Docker Compose

## Pornire (mediu de dezvoltare)
1. Creează fișierul `.env` în rădăcina proiectului:
   ```
   POSTGRES_DB=second_chance_paws
   POSTGRES_USER=scp
   POSTGRES_PASSWORD=scp_dev_password
   ```
2. Pornește baza de date:
   ```bash
   docker compose up -d
   ```
3. pgAdmin: http://localhost:5050 (serverul apare automat; parola este cea din `.env`)
4. Postgres este disponibil pe `localhost:5433`

## Documentație
Documentația LaTeX se află în `docs/documentatie.tex`.
