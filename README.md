# Planet Jersey

Planet Jersey is a full-stack CRUD application that allows users to buy a jersey from the inputted database which is also created in this web.

---

## Getting Started

To run the project locally, follow the steps below.

### Installation

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
### Importing the Database

A SQL dump file is included in the project for quick setup. Make sure you have created a MySQL database and don't forget to activate the localhost in XAMPP

1. Login to MySql

   ```
   mysql -u root -p
   ```

2. Create the database (if not already created)

   ```
   CREATE DATABASE jersey_store_db;
   ```

3. Exit MySql and import the dump
   ```
   mysqldump -u root -p jersey_store_db --no-data > planet_jersey_db.sql
   ```

After importing, the database will contain all required tables.

## Usage

1. Visit the frontend in your browser:
   (user)
   ```
   http://localhost:5173
   ```
   (admin)
   ```
   http://localhost:5173/admin
   ```

2. You can now use it for:
   - Adding Jerseys (admin)
   - Edit and delete products (admin)
   - View your inputted data (admin)
   - Add item to carts (users)
   - Select jersey type in homepage (users)
  
 ## License

Distributed under the GPL-v3 License. See `LICENSE` for more information.

Made with ❤️ for football fans worldwide
