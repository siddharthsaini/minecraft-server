# minecraft-server
just another mc server with ngrok

# Windows:
1. install ngrok 
2. from cmd in the server directory run: ngrok-win tcp -regin in 25565
3. another cmd session in the same directory run: java -Xmx1024M -Xms1024M -jar server.jar nogui

# Linux / Mac
1. from shell in the same server dir run: ./ngrok-ubu tcp -regin in 25565
3. another shell session in the same directory run: java -Xmx1024M -Xms1024M -jar server.jar nogui
