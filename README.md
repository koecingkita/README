# README
My Personal Repository
<?php

namespace Koecingkita;

class About extends Me
{
    /**
     * Display current life motives.
     *
     * @param null
     * @return string
     */
    public function getCurrentProfile(): string {
        return 'i like coding';
    }
    
    /**
     * Display user's 'secret' detail.
     *
     * @param null
     * @return array
     */
    private function getProfilingDetail(): array {
        return [
            'age' => 22,
            'email' => 'ibnuyusu1243@yahoo.com'
        ];
    }

    /**
     * Display Skills & Knowledge.
     *
     * @param null
     * @return array of class
     */
    public function getDailyKnowledge(): array {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            MySql::class,
            BootStrap::class
        ];
    }
}
