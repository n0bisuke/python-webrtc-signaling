
# PythonのWebRTCシグナリングサーバーサンプルです。

## 使い方

[こちらをもとにしています。](https://github.com/dpallot/simple-websocket-server)

```
pip install git+https://github.com/dpallot/simple-websocket-server.git
```

* シグナリングサーバー起動 ポート8000

```
python signaling.py
```

* Webサーバー起動 ポート8001

```
python -m SimpleHTTPServer 8001
```

## 記事

[PythonでWebRTCのシグナリングサーバーを作ってみる #webrtcjp](https://qiita.com/n0bisuke/items/952c55b9ce464039749a)
