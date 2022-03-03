# http

http post get.

## 安装

``` cmd
composer require ebcms/http
```

## 用例

``` php
\Ebcms\Http\Http::get(string $url, $timeout = 5, $ssl_verify = false);
\Ebcms\Http\Http::post(string $url, array $data = [], $timeout = 5, $ssl_verify = false);
```
