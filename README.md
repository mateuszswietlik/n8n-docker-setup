# n8n Docker Setup (z PostgreSQL)

Ten projekt zawiera kompletną konfigurację `n8n` do uruchomienia w środowisku produkcyjnym z użyciem Dockera i bazy danych PostgreSQL.

## 🧰 Co zawiera repozytorium

- `docker-compose.yml` – konfiguracja Dockera dla n8n i PostgreSQL
- `.env` – zmienne środowiskowe (login, hasło, dane bazy)
- Gotowe do uruchomienia komendą: `docker compose up -d`

## 🚀 Jak uruchomić

1. Skonfiguruj plik `.env`
2. W katalogu z `docker-compose.yml`, uruchom:

   ```bash
   docker compose up -d
   ```

3. Wejdź w przeglądarce pod: `http://<TWOJE_IP>:5678`

## 🔐 Dane logowania (przykład)

- login: `admin`
- hasło: `supertajnehaslo`

## 🧠 Wymagania

- Docker + Docker Compose
- min. 2 CPU, 2–4 GB RAM

## 🛠️ Autor

Repozytorium stworzone przez [Mateusza Świetlika](https://www.linkedin.com/in/mateuszswietlik/)