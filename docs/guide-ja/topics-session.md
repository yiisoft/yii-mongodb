セッションコンポーネントを使用する
==================================

`Session` コンポーネントを使用するためには、[インストール](installation.md) の節で説明した接続の構成に加えて、`session` コンポーネントを `Yiisoft\Db\MongoDb\Session` として構成する必要があります。

```php
return [
    //....
    'components' => [
        // ...
        'session' => [
            'class' => 'Yiisoft\Db\MongoDb\Session',
        ],
    ]
];
```
