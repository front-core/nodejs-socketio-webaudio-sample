## Node.js + Express + Socket.io + WebAudio on Heroku
NodeJS(Express)、Socket.io、WebAudioを使って、  
各デバイス間で双方向通信して音声を再生するサンプルをHerokuにデプロイ。  
※WebAudioのドラムの[サンプル](https://github.com/front-core/web-audio-api-drums-sample)に機能を追加したものになります。

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

※ ローカルの場合は、index.htmlのこのコメントを外してlocalhostにconnect(Line120)  
```
// var socketio = io.connect('http://localhost:8000');
```
