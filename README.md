# planet-jersey
Installation

To run the project locally, follow the steps below.

1. Clone the repo
```
git clone https://github.com/MulkyAyyubi/planet-jersey.git
cd planet_jersey
```

2. Install dependencies for both backend and frontend
```
cd backend && pnpm install
cd ../frontend && pnpm install
```

4. Add environment variables by copying .env.example
```
cd ..
cp backend/.env.example backend/.env
cp frontend/.env.example frontend/.env
```

6. Start development servers
```
Backend:

cd backend
npm run start
```
```
Frontend:

cd ../frontend
npm run dev
```
