
# Fake Backend (json-server)
This is a mock backend for the HR project using `json-server`.

### 🔗 Backend (JSON Server on Render)
Live: [https://hrapp-backend-8nau.onrender.com/api/employees]
Github: (https://github.com/danielanthonyO/hrApp_backend.git)

Link: ["https://dashboard.render.com/web/srv-d1639oqli9vc73acrcdg/deploys/dep-d163asili9vc73acsju0"]

## How to Run
1. Install json-server globally if you haven't:

```bash
npm install -g json-server
```

2. Start the server:

```bash
json-server --watch db.json --port 3001
```

3. API Endpoints available:

- GET    /employees
- POST   /employees
- PUT    /employees/:id
- DELETE /employees/:id

## Note:
Ensure your frontend fetches data from 
`http://localhost:3001/employees`
`https://hrapp-backend-8nau.onrender.com/api/employees`
