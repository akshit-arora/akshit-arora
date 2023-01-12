### Hey There, Welcome!

```php
<?php

namespace AkshitArora;

/**
 * What if I was just another PHP Script? Or may be this could be a bot emulating me?
 */
class About extends Me implements Introduction
{
    /**
     * First things first!
     *
     * @return string
     */
    public function getName(): string
    {
        return 'Akshit Arora';
    }
    
    /**
     * Geographical location
     *
     * @return string
     */
    public function getLocation(): string
    {
        return 'Ahmedabad, India';
    }
    
    /**
     * Languages known, in the order of fluency
     *
     * @return array
     */
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
                'Node.js',
                'Java',
                'Python',
                'C#',
            ]
        ];
    }

    /**
     * Project domains on which I've worked on.
     *
     * @return array
     */
    public function getProjectTypes(): array
    {
        return [
            'e-Commerce applications',
            'ERP for SMEs',
            'CRMs',
            'Wordpress Websites',
            'APIs',
            'Automating day-to-day tasks',
            'Something that could make life easier',
        ];
    }
    
    /**
     * What I like to do in my life
     *
     * @return array
     */
    public function getPassions(): array
    {
        return [
            'Coding',
            'Social Work',
            'Travelling',
            'Eating Food (Veg.)'
        ];
    }

    /**
     * My goals for the future
     *
     * @return array
     */
    public function getFutureGoals(): array
    {
        return [
            'To contribute to open source. (Work in progress)',
            'To create a SIMPLE erp. (Ideation in progress)',
            'To create a personal AI-assistant. (Ideation in progress)',
        ];
    }
}
```

<!---
akshit-arora/akshit-arora is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
