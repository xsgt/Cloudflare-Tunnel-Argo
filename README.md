

## 开始安装部署

- 1、安装
```
bash <(curl -Ls https://raw.githubusercontent.com/xsgt/Cloudflare-Tunnel-Argo/main/install-argo.sh)
```

- 2、服务启动
```
sudo cloudflared service install
```
- 3、重启服务
```
sudo systemctl restart cloudflared
```
- 4、系统自动启动
```
sudo systemctl enable cloudflared
```
- 5、停止服务
```
sudo systemctl stop cloudflared
```
- 6、查看服务状态
```
sudo systemctl status cloudflared
```

