```php
namespace Josluistanic;

class About extends Me
{
    public function getLanguages(): array
    {
        return [
            'en' => 'English',
            'es' => 'Spanish',
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            TailwindCss::class,
            Alpine::class,
            Laravel::class,
            Livewire::class,
            JavaScript::class,
            Ux::class,
        ];
    }

    public function contact(): array
    {
        return [
            'Email' => 'dev@josluistanic.com',
            'Web' => 'https://josluistanic.com',
            'LinkedIn' => 'https://www.linkedin.com/in/joseluistanic/',
        ];
    }

    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'HardSoft Ecuador',
                'position' => 'Web Developer'
            ]
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
  
<!---
Josluistanic/Josluistanic is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
