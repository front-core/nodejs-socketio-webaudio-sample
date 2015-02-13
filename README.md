## Node.js(express) + Socket.IO + Web Audio API on Heroku
Node.js(express)、Socket.IO、Web Audio APIを使って、  
各デバイス間で双方向通信して音声を再生するサンプルをHerokuにデプロイ。  
※Web Audio APIのドラムの[サンプル](https://github.com/front-core/web-audio-api-drums-sample)に機能を追加したものになります。

### URL
https://nodejs-socketio-webaudio.herokuapp.com/


### Install and Running(local)
```
git clone https://github.com/front-core/nodejs-socketio-webaudio-sample.git
cd nodejs-socketio-webaudio-sample
npm install
node web.js
```
Access to [http://localhost:8000](http://localhost:8000)  

※ ローカルの場合は、index.htmlのこのコメントを外してlocalhostにconnect  
```
// var socketio = io.connect('http://localhost:8000');
```
