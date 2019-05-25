```
cd server/
docker-compose up -d
docker exec -it server_flask_1 bash
pip install -r requirements.txt
docker-compose stop
docker-compose start
```
