# Virtual Tour Demo App using Pallenium
## How to Serve `index.html` for Pannellum via Localhost

To avoid CORS/security issues when loading JSON assets and textures, you need to run a local HTTP server instead of opening the file directly.

---

## 1. Using Python’s Built-in HTTP Server

1. Open a terminal and navigate to your project folder (where `index.html` resides):  
   ```bash
   cd /path/to/your/project
   ```

2. Start the server on port 8000
   ```bash
   # If you have Python 3 installed:
   python3 -m http.server 8000
   ```

3. In your Browser, go to:
   ```bash
   http://localhost:8000/index.html
   ```

