# favorite-nginx
Selected favorite nginx modules and resources.

Thanks for [awesome-resty](https://github.com/bungle/awesome-resty).

## Contents
* [Documents](#documents)
* [Nginx modules](#nginx-modules)
* [Resty(C) modules](#restyc-modules)
* [Resty(lua) modules](#restylua-modules)
* [Test](#test)
* [Tools](#tools)
* [Books](#books)
* [Known Projects](#known-projects)
* [Conference](#conference)
* [My Own Projects](#my-own-projects)


## Documents
* [nginx docs](http://nginx.org/en/docs/) - nginx reference manual
* [nginx unit](http://unit.nginx.org/) - nginx controller and router
* [openresty on github](https://github.com/openresty) - All code of agentzh
* [luajit ffi docs](http://luajit.org/ext_ffi.html) - luajit ffi docs
* [ngx lua api docs](https://github.com/openresty/lua-nginx-module/#nginx-api-for-lua) - ngx lua api docs
* [more nginx resources](https://github.com/fcambus/nginx-resources) - A collection of resources covering Nginx, Nginx + Lua, OpenResty and Tengine
* [C/C++ resources](https://github.com/fffaraz/awesome-cpp) - A curated list of awesome C/C++ frameworks, libraries, resources, and shiny things

## Nginx modules
* [echo-nginx-module](https://github.com/openresty/echo-nginx-module) - An Nginx module for bringing the power of "echo", "sleep", "time" and more to Nginx's config file
* [libsregex](https://github.com/openresty/sregex) -  A non-backtracking NFA/DFA-based Perl-compatible regex engine library for matching on large data streams
* [ngx_replace_filter](https://github.com/openresty/replace-filter-nginx-module) - Streaming regular expression replacement in response bodies
* [nginx-rtmp-module](https://github.com/arut/nginx-rtmp-module) - NGINX-based Media Streaming Server
* [nginx-sticky-module](https://github.com/bymaximus/nginx-sticky-module-ng) - add a sticky cookie to be always forwarded to the same upstream server
* [nginx-module-vts](https://github.com/vozlt/nginx-module-vts) - Nginx virtual host traffic status module
* [ngx_http_proxy_connect_module](https://github.com/chobits/ngx_http_proxy_connect_module) - provides support for the "CONNECT" HTTP method

## Resty(C) modules
* [lua-nginx-module](https://github.com/openresty/lua-nginx-module) - Embed the power of Lua into Nginx
* [stream-lua-nginx-module](https://github.com/openresty/stream-lua-nginx-module) - Embed the power of Lua into NGINX TCP servers
* [lua-ssl-nginx-module](https://github.com/openresty/lua-ssl-nginx-module) - NGINX C module that extends ngx_http_lua_module for enhanced SSL/TLS capabilities
* [ngx_http_lua_upstream](https://github.com/openresty/lua-upstream-nginx-module) - Nginx C module to expose Lua API to ngx_lua for Nginx upstreams

## Resty(lua) modules

### Core
* [lua-resty-core](https://github.com/openresty/lua-resty-core) - New FFI-based Lua API for the ngx_lua module
* [lua-resty-string](https://github.com/openresty/lua-resty-string) - String utilities and common hash functions for ngx_lua and LuaJIT
* [lua-resty-lock](https://github.com/openresty/lua-resty-lock) - Shared dict lock
* [lua-resty-lrucache](https://github.com/openresty/lua-resty-lrucache) - This library implements a simple LRU cache for OpenResty and the ngx_lua module.
* [lua-resty-upstream-healthcheck](https://github.com/openresty/lua-resty-upstream-healthcheck) - Health-checker for Nginx upstream servers
* [lua-resty-limit-traffic](https://github.com/openresty/lua-resty-limit-traffic) - Lua library for limiting and controlling traffic in OpenResty/ngx_lua
* [lua-resty-upload](https://github.com/openresty/lua-resty-upload) - Streaming reader and parser for HTTP file uploading based on ngx_lua cosocket
* [lua-resty-shdict-simple](https://github.com/openresty/lua-resty-shdict-simple) - Simple application-oriented interface to OpenResty's shared dictionary API
* [lua-resty-dns](https://github.com/openresty/lua-resty-dns) - Lua DNS resolver for the ngx_lua based on the cosocket API
* [lua-resty-balancer](https://github.com/openresty/lua-resty-balancer) - A generic consistent hash implementation for OpenResty/Lua

### Encode & Decode
* [lua-cjson](https://github.com/openresty/lua-cjson) - Lua cJSON is a fast JSON encoding / parsing module for Lua
* [lua-cmsgpack](https://github.com/chronolaw/lua-cmsgpack) - Lua cmsgpack is a fast msgpack encoding / parsing module for Lua
* [lua-resty-json](https://github.com/cloudflare/lua-resty-json) - Json lib for lua and C
* [lua-resty-msgpack](https://github.com/chronolaw/lua-resty-msgpack) - Lua messagepack for ngx_lua/stream_lua/OpenResty
* [lua-resty-snappy](https://github.com/bungle/lua-resty-snappy) - LuaJIT FFI bindings for Snappy, a fast compressor/decompressor

### Database
* [lua-resty-redis](https://github.com/openresty/lua-resty-redis) - Lua Redis client driver for the ngx_lua based on the cosocket API
* [lua-resty-ssdb](https://github.com/LazyZhu/lua-resty-ssdb) - Lua ssdb client driver for the ngx_lua based on the cosocket API
* [lua-resty-mysql](https://github.com/openresty/lua-resty-mysql) - Lua MySQL client driver for ngx_lua based on the cosocket API
* [lua-resty-qless](https://github.com/pintsized/lua-resty-qless) - Lua binding to Qless (Queue / Pipeline management) for OpenResty / Redis

### Backend
* [lua-resty-http](https://github.com/pintsized/lua-resty-http) - Lua HTTP client cosocket driver for OpenResty / ngx_lua
* [lua-resty-websocket](https://github.com/openresty/lua-resty-websocket) - WebSocket support for the ngx_lua module (and OpenResty) 

### Others
* [lua-resty-logger-socket](https://github.com/cloudflare/lua-resty-logger-socket) - Nonblocking remote access logging for Nginx
* [lua-resty-rsa](https://github.com/doujiang24/lua-resty-rsa) - RSA functions for LuaJIT
* [lua-resty-sniproxy](https://github.com/fffonion/lua-resty-sniproxy/) - SNI Proxy based on the ngx_lua cosocket API
* [lua-resty-iputils](https://github.com/hamishforbes/lua-resty-iputils) - Collection of utility functions for working with IP addresses
* [lua-resty-mlcache](https://github.com/thibaultcha/lua-resty-mlcache) - Fast and automated multi-level cache for OpenResty
* [lua-resty-jit-uuid](https://github.com/thibaultcha/lua-resty-jit-uuid) - A pure LuaJIT (no dependencies) UUID library tuned for performance
* [lua-resty-worker-events](https://github.com/Kong/lua-resty-worker-events) - Inter process events for Nginx worker processes
* [luafilesystem](https://github.com/spacewander/luafilesystem) - Reimplement luafilesystem via LuaJIT FFI.


 
## Test
* [nginx-systemtap-toolkit](https://github.com/openresty/nginx-systemtap-toolkit) - Very useful tools for nginx
* [stap++](https://github.com/openresty/stapxx) - Simple macro language extensions to systemtap
* [test-nginx](https://github.com/openresty/test-nginx) - Data-driven test scaffold for Nginx C module and OpenResty Lua library development
* [ngx_google_perftools_profiler](https://github.com/chronolaw/ngx_google_perftools_profiler_module) - A better tools for nginx with google_perftools
* [lua-resty-busted](https://github.com/thibaultcha/lua-resty-busted) - A little hack to test OpenResty scripts with busted
* [lua-resty-repl](https://github.com/saks/lua-resty-repl) - A debugger console for OpenResty
* [wrk](https://github.com/wg/wrk) - Like ab
* [travis-ci](https://travis-ci.org) - travis-ci

## Tools
* [opm](https://github.com/openresty/opm) - Official package management system for OpenResty
* [resty-cli](https://github.com/openresty/resty-cli) - Fancy command-line utilities for OpenResty 


## Books
* [OpenResty Best Practices(Chinese)](https://github.com/moonbingbing/openresty-best-practices) ([GitBook](https://www.gitbook.com/book/moonbingbing/openresty-best-practices/details))
* [agentzh's Nginx Tutorials(Chinese)](https://github.com/openresty/nginx-tutorials/tree/master/zh-cn)
* [Programming OpenResty](https://github.com/openresty/programming-openresty)

## Known Projects
* [upyun-resty](https://github.com/upyun/upyun-resty) - UPYUN's open source software for OpenResty development
* [Kong](https://github.com/Mashape/kong) - API Gateway & Microservice Management
* [Lapis](http://leafo.net/lapis/) - A web framework for Lua or MoonScript powered by OpenResty
* [lor](https://github.com/sumory/lor) - a fast, minimalist web framework for lua based on OpenResty(中文)
* [Orange](https://github.com/sumory/orange) - A Gateway based on OpenResty(Nginx+lua) for API Monitoring and Management.
* [verynginx](https://github.com/alexazhou/VeryNginx) - A very powerful and friendly nginx which provide WAF, Control Panel, and Dashboards

## Conference
* [2016](http://con.openresty.org/cn/2016/) - OpenResty Con 2016
* [2017](http://con.openresty.org/cn/2017/) - OpenResty Con 2017

## My Own Projects
* [openresty_dev](https://github.com/chronolaw/openresty_dev) - OpenResty/Lua Programming
* [annotated_nginx](https://github.com/chronolaw/annotated_nginx) - 注释nginx，学习研究源码




