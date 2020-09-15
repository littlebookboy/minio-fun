# minio-fun

```
npm install
```

若沒有過，噴 

```
stack Error: EACCES: permission denied, mkdir '/Users/gene/Workspace/minio/minio-fun/node_modules/fsevents/build'
```

試試用

```
npm install --no-optional
```

設置 .env，例如

```
END_POINT=localhost # 這邊不能帶 port，請用 PORT 參數指定
PORT="9009" # 若使用 https 要用 443
ACCESS_KEY=geneqq
SECRET_Key=qqqq3333
```

接著執行

```
node main.js
```

開啟 localhot:8081，index.html 進入點是在 main.js 最下面 `server.listen(8081)` 指定的。
