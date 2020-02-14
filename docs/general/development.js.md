# Development Configuration

## `Express` 
Express.js, or simply Express, is a web application framework for Node.js, released as free and open-source software under the MIT License. It is designed for building web applications and APIs. It has been called the de facto standard server framework for Node.js. [`More Info`](https://expressjs.com/)

## `Express Middleware`
Express middleware are functions that execute during the lifecycle of a request to the Express server. Each middleware has access to the HTTP request and response for each route (or path) it's attached to. In fact, Express itself is compromised wholly of middleware functions. [`More Info`](https://expressjs.com/en/guide/writing-middleware.html)

    // make express server
    const app = express();

    // static files
    app.use(express.static(PUBLIC_PATH));

## `CookieParser` 
Parse Cookie header and populate req.cookies with an object keyed by the cookie names. Optionally you may enable signed cookie support by passing a secret string, which assigns req.secret so it may be used by other middleware. [`More info`](https://www.npmjs.com/package/cookie-parser)

    // cookie
    app.use(cookieParser())

