# myrm1


### clash 代理
记得要打开wifi开关
```
clash
cd /home/clash/
nohup ./clash -d . &
export HTTPS_PROXY="http://127.0.0.1:4780"
export ALL_PROXY="socks5://localhost:4781"
export HTTP_PROXY="http://127.0.0.1:4780"
## 测试是否成功连接
wget http://remarkable.com

```


### 同步画面  reStream


基于默认的ip地址的,所以确认usb连上remarkable且可以免密登陆它

```
ssh root@10.11.99.1
cd /Users/hamlin/Documents/remarkable/reStream
./reStream.sh
```


### 传输pdf

```
cd ~/Documents/remarkable/
bash pdf2remarkable.sh  -r 英语常见问题解答大词典.pdf
```


### Telegram bot 传输

```
### 暂时还没看
https://github.com/Davide95/remarkaBot
```
