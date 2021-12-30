# Nodejs - Express - MongoDB

OpenClassrooms
Passez au Full Stack avec Node.js, Express et MongoDB
https://openclassrooms.com/fr/courses/6390246-passez-au-full-stack-avec-node-js-express-et-mongodb

## MongoDB

```bash
# docker compose mongodb
cd backend/mongodb/
docker-compose up -d
docker ps

# mongodb client
sudo apt install mongodb-clients
mongo admin -u root -p rootpassword

# GUI mongodb
wget https://downloads.mongodb.com/compass/mongodb-compass_1.29.6_amd64.deb
sudo dpkg -i mongodb-compass_1.29.6_amd64.deb
mongodb-compass
```

## Bakend

```bash
cd backend
npm install
nodemon server
```

## Frontend

```bash
cd frontend
npm install
npm run start
```
