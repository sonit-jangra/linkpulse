# LinkPulse

A high-performance URL shortener and real-time click analytics platform. LinkPulse pairs an asynchronous, cached backend engine with a minimalist web dashboard.


### 1. Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Copy the example environment file and configure variables as needed:
   ```bash
   cp .env.example .env
   ```

3. Start PostgreSQL and Redis containers:
   ```bash
   docker compose up -d
   ```

4. Install dependencies:
   ```bash
   npm install
   ```

5. Start the development server:
   ```bash
   npm run dev
   ```

   The backend will be available at `http://localhost:5000`.

---

### 2. Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the Next.js development server:
   ```bash
   npm run dev
   ```

   The frontend dashboard will be available at `http://localhost:3000`.

---

## Key Features

- **Fast URL Redirection**: Uses Redis caching to resolve target URLs with minimal latency.
- **Real-Time Dashboard**: Clean UI to create custom short links, view click counters, copy links, and inspect analytics modals.
MADE BY SONIT JANGRA