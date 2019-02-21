Install Instructions

1.  Clone
2.  Composer install
3.  Run Tests on windows:

 vendor\bin\phpunit --bootstrap vendor\autoload.php tests\EmailTest

mac: 
 vendor/bin/phpunit --bootstrap vendor/autoload.php tests/EmailTest
_________

Car.php :
Since this is an ‘abstract’ class, it means we are able to make other versions of the class ‘Car’ with a different name but with the same variables ($wheels, $make, etc) and functions (accelerate, decelerate).

In CarTest.php:
    public function testCanCreateFord 
    -This creates a copy of the class car but named 'Ford'. ‘Ford’ now holds the same variables and functions of the ‘Car’ class

Ford.php :
This is the ‘Ford’ class which is made from the ‘Car’ class’. It holds the same variables and functions as the ‘Car’ class but we can now change the values of those variables and functions. 
