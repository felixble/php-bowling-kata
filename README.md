# PHP-Bowling-Kata

Implementation of Uncle Bob's [bowling-kata](http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata) in PHP. 
With mutation testing I found out that one test case is missing: Rolling a spare with different pins (e.g. 7 and 3).

## Usage

Install dependencies:

    composer install
    
Run tests:

    composer run-script test
    
Run mutation tests

    composer run-script mutation-test