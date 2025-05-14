## 🧑‍💻 About Me in Code

```php
<?php

namespace SharifUddin;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplaces' => [
                [
                    'company' => 'FOCUS - IT Services',
                    'position' => ''Full-Stack Developer (Laravel & React) / Software Engineer',
                    'location' => 'Islamabad'
                ],
                [
                    'company' => 'Freelance / Self-employed',
                    'position' => 'Full-Stack Developer (Laravel & React)'
                ]

            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            VueJS::class,
            ReactJS::class,
            Javascript::class,
            Python::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To become a Machine Learning Engineer and contribute to AI and open source.';
    }
}
