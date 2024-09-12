# aws-sam

https://gist.github.com/wongcyrus/3a65acb1f8f5405e15342f7e0d76d1d9

# setup

git clone https://github.com/mxcheung/aws-sam.git

sam init --runtime python3.9
cd ./sam-app
sam build
sam local invoke HelloWorldFunction --event events/event.json

