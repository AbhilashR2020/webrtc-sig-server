webrtc-sig-server
=================

Signalling server for web-rtc-app written in Erlang.

live demo is available at http://gwt-webrtc.appspot.com/

It is intened to work with gwt-webrtc-demo application. Based on YAWS (http://yaws.hyber.org/) HTTP serwer and
uses websockets as a transport layer for realtime messages.

#### Building and running

```sh
./rebar get-deps
./rebar compile
./run.sh
next in erlang shell
1>application:start(wrtc_demo_app).
```


license http://www.gnu.org/licenses/gpl.html
