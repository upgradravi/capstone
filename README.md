## Usage:
```
# Install dependencies
npm install

# Start server
node server.js
```
## API details
- GET /
    - returns "Hello World"
- GET /load
    - query params:
        - scale -> time in milliseconds  for which CPU will be blocked for some time (default= 0ms to 10ms)
    - returns "OK" after execution

## Notes:
- App runs on port 8081
