设置代理：前提你得有代理哈
# 设置代理：

```bash
//http || https
git config --global http.proxy 127.0.0.1:7890
git config --global https.proxy 127.0.0.1:7890

//sock5代理
git config --global http.proxy socks5 127.0.0.1:7891
git config --global https.proxy socks5 127.0.0.1:7891
```

# 查看代理：

```bash
git config --global --get http.proxy
git config --global --get https.proxy
```

# 取消代理：

```bash
git config --global --unset http.proxy
git config --global --unset https.proxy
```