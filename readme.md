<h1 align="center">
	<img width="350" src="https://i.imgur.com/lHEi8rT.png" alt="awesome swoole">
</h1>

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of Swoole.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

---

## Table of Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Documentation](#documentation)
- [Development](#development)
- [Process](#process)
- [Server](#server)
- [Client](#client)
- [Algorithm](#algorithm)
- [Framework](#framework)
- [Database](#database)
- [Integration](#integration)
- [Others](#others)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

---

## Documentation
- [Swoole Docs](https://www.swoole.co.uk/docs) - Official Swoole documentaion in English.
- [Swoole Examples](https://github.com/swoole/swoole-src/tree/master/examples) - Official examples in Github.
- [Another Swoole Examples](https://github.com/chenchaojie/Swoole) - Another personal Swoole examples for learning purpose.
- [Concise Guide (Outdated)](https://github.com/LinkedDestiny/swoole-doc) - A personal concise guide for Swoole.
- [Swoole Study Notes](https://github.com/szyhf/swoole_study) - A collection of personal study notes for Swoole beginners.

## Development

- [Swoole IDE Helper](https://github.com/eaglewu/swoole-ide-helper) - Auto completion, trigger suggest and view docs for Swoole in editor.
- [MyQEE](https://github.com/myqee/server) - A wrapper library for Swoole.
- [Auto Reload](https://github.com/swoole/auto_reload) - Official hot reload tool using inotify.

## Process
- [Donkey](https://github.com/osgochina/Donkey) - An async crontab application by Swoole.
- [multiprocess](https://github.com/kcloze/multiprocess) - Easy to make the common PHP/Python/JS...script change daemon and multi-process execution.
- [statistics](https://github.com/smalleyes/statistics) - A web monitor system by Swoole.
- [swoole-jobs](https://github.com/kcloze/swoole-jobs) - Dynamic multi process worker queue base on swoole, like gearman but high performance.

## Server
- [hprose-swoole](https://github.com/hprose/hprose-swoole) - Hprose asynchronous client & standalone server based on swoole.
- [mqtt-server](https://github.com/swoole/mqtt-server) - A simple swoole mqtt server.
- [Dora-RPC](https://github.com/xcl3721/Dora-RPC) - An RPC For the PHP MicroService by Swoole.
- [swoole-grpc](https://github.com/CatsSystem/swoole-grpc) - A GRPC implement based on Swoole Http2 Server.

## Client

- [php-amqplib](https://github.com/swoole/php-amqplib) - A PHP coroutine client for RabbitMQ base on Swoole extension.
- [zmq](https://github.com/albinekb/open-pip-cli) - ZeroMQ bindings for Swoole.
- [swoole-http-client](https://github.com/Moln/swoole-http-client) - An async http client in compatible with psr7 request and response.

## Algorithm

- [BloomFilter](https://github.com/swoole/BloomFilter) - A Bloom Filter extension with Swoole.

## Framework
- [Swoole Framework](https://github.com/matyhtf/framework) - An official Swoole framework.
- [Swoole Distributed](https://github.com/SwooleDistributed/SwooleDistributed) - A distributed Swoole framework.
- [TSF](https://github.com/Tencent/tsf) - A coroutine and Swoole based php server framework in Tencent.
- [easyswoole](https://github.com/easy-swoole/easyswoole) - Use swoole easily just like echo "hello world";.
- [Swoft](https://github.com/swoft-cloud/swoft) - A modern high performance AOP and coroutine PHP Framework based on Swoole.
- [Blink](https://github.com/bixuehujin/blink) - A high performance web framework and application server in PHP.
- [FastD](https://github.com/fastdlabs/fastD) - A high performance PHP API framework.
- [zhttp](https://github.com/keaixiaou/zhttp) - A light weight web framework.
- [php-msf](https://github.com/pinguo/php-msf) - A micro service framework developed by [Camera 360](http://www.camera360.com) team.
- [mixphp](https://github.com/mixstart/mixphp) - A light weight yet hight performance web framework.
- [GroupCo](https://github.com/fucongcong/GroupCo) - A web framework for API, Http server, RPC server, micro service and high concurrency use cases.

## Database
- [Sworm](https://github.com/heikezy/Sworm) - A PHP NotORM-like database library based on Swoole for simple working with data in the database.
- [swoole2-mysqlpool](https://github.com/yangxikun/swoole2-mysqlpool) - A MySQL connection pool.
- [laravel-swoole-cp](https://github.com/breeze2/laravel-swoole-cp) - A swoole connection pool for Laravel.
- [mysql-proxy](https://github.com/swoole/mysql-proxy) - A MySQL proxy with connection pool and read/write splitting support.

## Integration
- [laravel-swoole](https://github.com/swooletw/laravel-swoole) - ❤️ A high performance HTTP sever based on Swoole. Speed up your Laravel or Lumen applications. This repo is maintained by Swoole Taiwan Community.
- [Lawoole](https://github.com/lawoole/lawoole) - A combination framework with Swoole and Laravel.
- [laravel-swoole-jsonrpc](https://github.com/huang-yi/laravel-swoole-jsonrpc) - The JSON-RPC server and client based on Swoole, for Laravel and Lumen framework.
- [lumen-swoole-http](https://github.com/breeze2/lumen-swoole-http) - A bridge from Swoole to Lumen.
- [laravel-s](https://github.com/hhxsv5/laravel-s) - Speed up Laravel/Lumen by Swoole, 'S' means Swoole, Speed, High performance.
- [Slim-Swoole](https://github.com/pachico/slim-swoole) - Convenient library to run SlimPHP applications with Swoole.
- [zys](https://github.com/qieangel2013/zys) - A high performance service framework based on Yaf or Swoole.
- [yii2-swoole](https://github.com/liufee/yii2-swoole) - An integration with yii2 and Swoole.
- [phwoolcon](https://github.com/phwoolcon/phwoolcon)- An integration with Phalcon and Swoole.

## Others
- [jegarn](https://github.com/yaoguais/jegarn) - A chat system, based on Swoole, redis and msgpack.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Albert Chen](https://albert-chen.com/) has waived all copyright and related or neighboring rights to this work.


