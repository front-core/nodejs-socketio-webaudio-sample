## Node.js + Express + Socket.io + WebAudio on Heroku
NodeJS(Express)、Socket.io、WebAudioを使って、  
各デバイス間で双方向通信して音声を再生するサンプルをHerokuにデプロイ。
※WebAudioのドラムの[サンプル](https://github.com/front-core/web-audio-api-drums-sample)に機能を追加したものになります。

### URL
https://nodejs-socketio-webaudio.herokuapp.com/


### install and running(local)
```
git clone 
cd 
npm install
node web.js
```
access to [http://localhost:8000](http://localhost:8000)  

※ index.htmlのこのコメントを外してローカルにconnectする(Line120)  
```
// var socketio = io.connect('http://localhost:8000');
```
