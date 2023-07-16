# 序言 - Draft
Remaster版本多了一些三倍速功能，讓重玩遊戲變得更加宜人。（手機版有些過動畫更可以跳過）

## local docker build command
```
docker run --user $(id -u):$(id -g) --rm -it -v $(pwd):/opt/mdbookdata mdbook:beta build
```