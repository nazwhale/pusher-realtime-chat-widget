# Realtime Chat Widget

A Realtime Chat Widget with a Ruby backend, made with the help of this [tutorial from Pusher](http://pusher.com/tutorials/realtime_chat_widget).

### Installation

First, clone the repo and navigate to the correct directory:

```
$ git clone git@github.com:nazwhale/pusher-realtime-chat-widget.git
$ cd pusher-realtime-chat-widget/src/ruby-sinatra
```
Install the relevant dependencies with [Bundler](http://bundler.io/):
```
$ gem install bundler     
$ bundle install
```
And run the program with the help of [Sinatra](http://www.sinatrarb.com/):
```
$ ruby chat.rb
```

### Use

Navigate to http://localhost:4567/ to see the side-by-side example or http://localhost:4567/chat.html to see the standalone example.

To send a Gif, simply type "Gif me a/some/an" followed by the name of the gif you would like to send.

The program will look up a gif from the [Giphy API](https://developers.giphy.com/) and insert it into the chat window.

Happy chatting!

![Imgur](https://i.imgur.com/tBD3gBK.png)
