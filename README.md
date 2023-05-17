# Minecraft_Server

啟動zerotier vpn 連線
```
sudo zerotier-one -d
```

加入zerotier vpn id="a84ac5c10a081caf"
```
sudo zerotier-cli join "a84ac5c10a081caf"
```

確認zerotier vpn 連線狀態
```
sudo zerotier-cli status
```

啟動minecraft fabric伺服器 nogui
```
java -jar fabric-server-mc.1.19.4-loader.0.14.19-launcher.0.11.2.jar nogui
```
