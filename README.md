```php
<?php
namespace AshBaker;
class About extends Me
{
    public function getCurrentWorkplace(): array
    {

    }
    public function getDailyKnowledge(): array
    {
        return [
            PHP::class,
            Javascript::class,
            HTML5::class,
            CSS::class,
            Mysql::class,
            Python::class,
        ];
    }

}
```

```javascript
const thai = {
  pronouns: "he",
  code: [Javascript, HTML5, CSS, Python,PHP,Mysql],
}
```
