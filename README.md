# auth-api
Node.js JWT Authentication API with MongoDB

## Setup
1. Install dependencies:
   npm install

2. Start MongoDB (localhost:27017)

3. Run the server:
   npm run dev

4. API endpoints:
   - POST /api/auth/register
   - POST /api/auth/login
   - POST /api/auth/refresh
   - POST /api/auth/logout
   - GET /api/profile (protected)
