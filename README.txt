Maak een .env file, met waarden voor de database, op basis van .env_example.
run: 
docker compose config
docker compose up --build -d

controleer de containers met:
docker compose ps

controleer de logs met:
docker compose logs app

Test de app op http://localhost:poortnummer

stop de service met:
docker compose down