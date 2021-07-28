### Hi there 👋

```php
<?php

namespace CharlesHMiranda;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Iam.Dev.Br',
                'position' => 'Founder'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Python::class,
            GoLang::class,
            MySQL::class,
            MongoDB::class,
            OracleDB::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to the community.';
    }
}
```
