# Employee Management System

## 🏃 Running the Employee Management System

### 1. Prerequisites

- Node.js installed
- Dependencies installed (skip if `node_modules` already exists)

```bash
cd employee-management-system
npm install
```

### 2. Run the App

#### Option 1: Single Command (recommended)

Starts the mock API (`json-server` on port 3001) and the Vite dev server together:

```bash
npm run dev:all
```

#### Option 2: Separate Terminals

Run in separate terminals:

**Terminal 1**

```bash
npm run server
# json-server on http://localhost:3001
```

**Terminal 2**

```bash
npm run dev
# Vite dev server
```

### 3. Open the App

Open the URL Vite prints (typically `http://localhost:5173`).

### 4. Configuration

The `.env` file sets:

```env
VITE_API_URL=http://localhost:3001
```

The API port should match the `json-server` port. No changes are needed unless you change the server port.

### 5. Other Scripts

```bash
npm run build
```

Type-check and produce a production build.

```bash
npm run preview
```

Serve the production build locally.

```bash
npm run lint
```

Run ESLint.
```