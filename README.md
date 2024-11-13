git clone [git@github.com:soma0822/chat_project.git](https://github.com/soma0822/chat_project.git)

cd chat_project

channels channels-redisをインストール
pip install channels channels-redis

redisをインストール
brew install redis

redisサーバーを起動
redis-server

daphneインストール
pip install daphne

daphneでchat_projectを起動
daphne -p 8000 chat_project.asgi:application
http://127.0.0.1:8000/room1/
