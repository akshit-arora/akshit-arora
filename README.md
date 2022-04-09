### Hey There, Welcome!

```php
<?php

namespace AkshitArora;

class About extends Me
{
    public function getName(): string
    {
        return 'Akshit Arora';
    }
    
    public function getLocation(): string
    {
        return 'Ahmedabad, India';
    }
    
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'TOPS Infosolutions Pvt. Ltd.',
                'position' => 'Sr. Software Engineer'         
            ]
        ];
    }
    
    public function getKnownLanguages(): array
    {
        return [
            'human' => [
                'English',
                'Hindi',
                'Gujarati',
                'Punjabi',
            ],
            'programming' => [
                'PHP',
                'Javascript',
            ]
        ];
    }

    public function getProjectTypes(): array
    {
        return [
            'e-Commerce',
            'ERP for SMEs',
            'CRMs',
            'Wordpress Websites',
            'APIs',
            'Anything challenging!'
        ];
    }
    
    public function getPassions(): array
    {
        return [
            'Coding',
            'Social Work',
            'Travelling',
        ];
    }

    public function getFutureGoal(): array
    {
        return [
            'To contribute to open source.',
            'To create a SIMPLE erp',
        ];
    }
}
```

Ok, I am not even that Geek! I even love pogramming memes! Here's a Meme for you! 👇

![Random Meme Here](https://random-memer.herokuapp.com/)

<!---
akshit-arora/akshit-arora is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
