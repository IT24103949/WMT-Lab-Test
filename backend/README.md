# Backend - Item Manager Lab Test

## Setup
1. Open a terminal inside the backend folder.
2. Run:
   ```bash
   npm install
   ```
3. Copy `.env.example` to `.env`
4. Update `MONGO_URI` if needed (for MongoDB Atlas, replace with your connection string).
5. Start the server:
   ```bash
   npm run dev
   ```

## MongoDB Setup
- Local: Install MongoDB Community Edition from https://www.mongodb.com/try/download/community and start the service.
- Cloud: Use MongoDB Atlas (free tier available).

## API Endpoints
- `GET /api/items`
- `GET /api/items/:id`
- `POST /api/items`
- `PUT /api/items/:id`
- `DELETE /api/items/:id`
