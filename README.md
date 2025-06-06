# Splitmate Backend

This is the backend service for **Splitmate**, a simple app to help friends split expenses easily.

## 🧰 Stack

- Node.js
- Express
- TypeScript

## ⚙️ Setup

### 1. Clone the Repo

```bash
git clone https://github.com/YOUR_USERNAME/splitmate-backend
cd splitmate-backend
```

### 2. Install Dependencies
```bash
npm install express
npm install --save-dev typescript ts-node-dev @types/express
```

### 3. Initialize TypeScript
```bash
npx tsc --init
```

### 4. Folder Structure
```pgsql
splitmate-backend/
├── src/
│   └── index.ts         # Express entry point
├── .gitignore
├── LICENSE
├── package.json
├── tsconfig.json
└── README.md
```

### 5. Example `src/index.ts`
```ts
import express from 'express';

const app = express();
const PORT = process.env.PORT || 3000;

app.use(express.json());

app.get('/', (_req, res) => {
  res.send('Welcome to Splitmate API');
});

app.listen(PORT, () => {
  console.log(`Server is running on http://localhost:${PORT}`);
});
```

### 🔁 Dev Script
Run the server in development mode:

```bash
npm run dev
```
Make sure your `package.json` includes:
```json
Copy code
"scripts": {
  "dev": "ts-node-dev --respawn --transpile-only src/index.ts"
}
```

### 📄 .gitignore Example
```bash
node_modules/
dist/
.env
```

### 📝 License
MIT — see `LICENSE` file.
