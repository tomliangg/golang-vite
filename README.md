# golang-vite-integration

The purpose of this repo is to demonstrate how to get vite to work with a backend server (i.e. go).  
The index.html template is consumed by the backend server. Vite's role here is to bundle js assets and then serve it back to the index.html; all contents are served from the backend server.

go http server is running at port 4000 while vite dev server is running at port 3000. To get started, start both go http server and vite dev server.

Reference: https://vitejs.dev/guide/backend-integration.html

## scripts

```bash
# start go http server
go run ./cmd/web
```

```bash
# start vite server:
npm run dev
```