============================
Welcome to janitoo_mosquitto
============================

As we need websockets support, we must install a recent version of mosquitto.

This is the job of this module. It installs packages for Debian, Ubuntu and Raspdebian using method listed here : http://mosquitto.org/download/

Configuration
=============

Websockets are listen on all addresses on port 9001. This is not secure.

We must use https://www.nginx.com/blog/websocket-nginx/ in production.

mqtt is on 1883.

