# Minecraft_Server

安裝ngrok 服務
```
curl -s https://ngrok-agent.s3.amazonaws.com/ngrok.asc | sudo tee /etc/apt/trusted.gpg.d/ngrok.asc >/dev/null && echo "deb https://ngrok-agent.s3.amazonaws.com buster main" | sudo tee /etc/apt/sources.list.d/ngrok.list && sudo apt update && sudo apt install ngrok
```

啟動ngrok port:25565
```
ngrok tcp 25565
```

啟動minecraft fabric伺服器 nogui
```
java -jar fabric-server-mc.1.20-loader.0.14.21-launcher.0.11.2.jar nogui
```