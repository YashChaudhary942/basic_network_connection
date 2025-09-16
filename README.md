Python Client–Server Handshake & Chat:
A simple demo of creating a TCP client–server connection in Python. The server asks the client for permission, and if accepted they can exchange messages

🚀Features:
1) Basic handshake: server → client request → accept/decline
2) Interactive message loop after handshake
3) Works on:
    Localhost (127.0.0.1)
    LAN (by using server’s IP address)
    WAN (via port-forwarding or a tunneling service like Ngrok)
4) Clear, minimal Python code — perfect for learning socket programming.

📂How It Works:
1) Server starts and listens on a chosen port.
2) Client connects and receives a request:
“Do you accept connection? (yes/no)”
3) If the client replies yes, the connection stays open and both sides can chat.
4) Type bye on either side to close the session.

⚠️ Notes:
1) For use across the internet, open/forward the port on the server’s router or use a tunnel (Ngrok, Cloudflare Tunnel, etc.).
2) This project is for educational purposes only — add authentication, encryption, and proper error handling before deploying publicly.
