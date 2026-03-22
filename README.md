# Cloud Task Manager - Zarządzanie zadaniami - Radosław Kuczyński 94612
 
Projekt natywnej aplikacji chmurowej realizowany w architekturze 3-warstwowej.
 
## Deklaracja Architektury (Mapowanie Azure)
Ten projekt został zaplanowany z myślą o usługach PaaS (Platform as a Service) w chmurze Azure.
 
| Warstwa | Komponent Lokalny | Usługa Azure |
| :--- | :--- | :--- |
| **Presentation** | React 19 (Vite) | Azure Static Web Apps |
| **Application** | API (.NET 9 / Node 24) | Azure App Service |
| **Data** | SQL Server (Dev) | Azure SQL Database (Serverless) |
 
## 🏗 Status Projektu i Dokumentacja
* [x] **Artefakt 1:** Zaplanowano strukturę folderów i diagram C4 (dostępny w `/docs`).
* [x] **Artefakt 2:** Środowisko wielokontenerowe uruchomione lokalnie (Docker Compose)
* [x] **Artefakt 3:** Działająca warstwa prezentacji (React + Vite w Dockerze).
* [x] **Artefakt 4:** Działająca warstwa logiki backendu (.Net9 + SQL Connection).
* [x] **Artefakt 5:** System jest gotowy na chmurę.
 
> **Informacja:** Ten plik będzie ewoluował. W kolejnych etapach dodamy tutaj sekcje 'Quick Start', opis zmiennych środowiskowych oraz instrukcję wdrożenia (CI/CD).
