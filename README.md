# devcompack.github.io
https://dev.saidelimam.com

## Local Development

### Option 1: Using Node.js (Recommended)

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the local preview server:
   ```bash
   npm run preview
   ```

   Or use the dev script:
   ```bash
   npm run dev
   ```

   The site will be available at `http://localhost:3000`

### Option 2: Using Python

If you have Python installed, you can use Python's built-in HTTP server:

**Python 3:**
```bash
python3 -m http.server 3000
```

**Python 2:**
```bash
python -m SimpleHTTPServer 3000
```

Then open `http://localhost:3000` in your browser.
