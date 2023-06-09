# Bills-App
A Bills application to learn Vue3 and NodeJS

## Technologies used:

### Backend:
- NodeJS
- Express
- MongoDB
- Mongoose

### Frontend:
- Vue3
- Vite
- TailwindCSS
- FontAwesome

## Project setup
### Backend:
#### Install pnpm
```npm install -g pnpm``` or ```yarn global add pnpm```
#### Install dependencies
```sh
cd bill-backend-app
pnpm install
```
#### Create a .env file in backend root directory
```sh
# ./bill-backend-app/.env
PORT=3000
VERSION=1.0.0
HOST=127.0.0.1
PORT=3000
CORS=http://localhost:5173
MONGO_USER=<your mongo user>
MONGO_PASS=<your mongo password>
MONGO_CLUSTER=<your mongo cluster>
MONGO_DB=<your mongo db>
```

#### Run the server
```sh
pnpm start
```

### Frontend:
#### Install dependencies
```sh
cd bill-frontend-app
pnpm install
```

#### Run the app
```sh
pnpm dev
```
