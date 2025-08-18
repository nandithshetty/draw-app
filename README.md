🎨 Collaborative Whiteboard App

This is a real-time collaborative drawing app built with Go (Golang) and WebSockets.
Multiple users can join the same board and draw together, with strokes synced live across all browsers.

✨ Features

🖌 Real-time collaborative drawing

👥 Presence tracking (see who is online)

⚡ Lightweight and fast (runs in a few MB of RAM)

🌐 Works on LAN or can be deployed online

🎨 Simple and clean frontend

🛠️ Tech Stack

Backend: Go + Gorilla WebSocket

Frontend: HTML, CSS, JavaScript (Torus.js, Blocks.css)

🚀 Running Locally (Windows)

Install Go on your system.

Clone this repo:

``git clone https://github.com/nandithshetty/draw-app.git
cd draw-app``


Run the server:

``go run cmd/draw.go``


Open your browser at:
👉 http://localhost:1243

🌐 Collaboration

Same PC: Open multiple browsers → draw in real-time.

Same Wi-Fi / LAN:

Find your local IP (ipconfig → IPv4).

Friends can join via:

``http://YOUR-IP:1243``


Over the Internet: Deploy on a cloud server (Render, Railway, DigitalOcean, AWS, etc.).

📸 Screenshot

Here’s how it looks in action: 
<img width="1531" height="852" alt="Screenshot 2025-08-19 013106" src="https://github.com/user-attachments/assets/de750b9b-3290-4b51-9e39-748f6a078d4d" />

📜 License

This project is open source under the MIT License.

⚡ Tip: Name your repo draw-app on GitHub so the clone link matches.
