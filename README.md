# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

## Running the Project with Docker

To run this project using Docker, follow these steps:

1. **Build the Docker Image**:
   ```bash
   docker-compose build
   ```

2. **Start the Services**:
   ```bash
   docker-compose up
   ```

3. **Access the Application**:
   Open your browser and navigate to `http://localhost:5173`.

### Project-Specific Details

- **Node.js Version**: 18-alpine (specified in the Dockerfile).
- **pnpm Version**: 10.4.1 (specified in the Dockerfile).
- **Exposed Port**: 5173 (mapped to the host).
- **Environment Variables**: Ensure any required `.env` file is placed in the project root if needed.

This setup ensures a consistent development environment using Docker.