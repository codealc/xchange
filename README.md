Xchange —  Financial Exchange Platform
A modular, full‑stack exchange prototype. Xchange demonstrates realtime orderbook and trade updates, order management, a matching engine, and separate services for frontend, API, engine, websocket server, and DB utilities.
# Xchange —  Financial Exchange Platform

A modular, full‑stack exchange prototype. Xchange demonstrates realtime orderbook and trade updates, order management, a matching engine, and separate services for frontend, API, engine, websocket server, and DB utilities.



## Tech Stack

**Client:** Next.js,ReactJS,TailwindCSS

**Server:** Node, Express,Typescript

**Websocket** : ws, a Node.js based websocket library

**Postgres:** Postgres used as RDBMS

**TradingView:** Financial data is displayed using the TradingView Charting Library.




## Features

- **Websocket Servers:** Provide real-time updates to clients about order status, book updates, and other relevant information.
- **Reduced Server Load:** By eliminating the need for frequent polling, websockets can significantly reduce the load on your server.
- **Queue:** A message queue system that handles order processing and updates.
- **API Server:** Handles incoming HTTP requests from the browser.
- **Redis:** In-memory operations for performance-critical tasks.
- **Chart:** TradingView Lightweight Charts integrated for real-time market data visualization, delivering a smooth and interactive trading experience.





    