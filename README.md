# Health Information System

A RESTful API and frontend for managing health programs and clients.

## Features
- Create health programs (e.g., TB, Malaria, HIV).
- Register and manage clients.
- Enroll clients in programs.
- Search clients with fuzzy matching.
- View client profiles with enrolled programs.
- Secure API with token-based authentication.
- Audit logging for actions.

## Setup
1. Clone the repo: git clone <repo-url>
2. Install dependencies: composer install
3. Configure .env with database and Sanctum settings.
4. Run migrations: php artisan migrate
5. Seed database: php artisan db:seed
6. Start server: phpkahrtisan serve
7. Access frontend at http://localhost:8000/index.html

## API Documentation
- Available at /api/documentation (Swagger).

## Testing
- Run tests: php artisan test

## Security
- Input validation via Laravel Form Requests.
- Token-based authentication with Sanctum.
- Audit logging for critical actions.
