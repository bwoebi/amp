Amp
====
Amp is a non-blocking concurrency framework for PHP applications

**Dependencies**

- PHP 5.5+

Optional PHP extensions may be used to improve performance in production environments and react to process control signals:

- [php-uv](https://github.com/chobie/php-uv) extension for libuv backends
- [pecl/libevent](http://pecl.php.net/package/libevent) for libevent backends ([download Windows .dll](http://windows.php.net/downloads/pecl/releases/libevent/0.0.5/))

**Installation**

```bash
$ git clone https://github.com/amphp/amp.git
$ cd amp
$ composer.phar install
```

**Community**

If you have questions stop by the [amp chat channel](https://gitter.im/amphp/amp) on Gitter.


**The Guide**

We've compiled all the information necessary to write concurrent applications using Amp in [the Guide](doc/guide.md).
