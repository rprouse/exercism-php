# Exercism PHP Track

## PHP Exercism on Windows

### Install PHP

- Download VS16 x64 Thread Safe ZIP from https://windows.php.net/download#php-8.0
- Unzip somewhere like `c:\bin\php`
- Add `c:\bin\php` to your path
- In a new terminal window, confirm with `php --version`

### Install PHPUnit

- In the browser, download `https://phar.phpunit.de/phpunit-9.5.phar` and save it to the root of your Exercism php directory `c:\src\Excercism\php` as `phpunit.phar`
- Go to the root of your exercism problems, `cd c:\src\Exercism`
- Test with `php phpunit.phar --version`

### Complete PHP Hello World

In the latest versions of PHPUnit, the test class name **must** match the filename, so you need to rename it.

This has been fixed for the next release. See [exercism/php#308](https://github.com/exercism/php/issues/308)

- Download the problem, `exercism download --exercise=hello-world --track=php`
- Rename `hello-world\hello-world_test.php` to `hello-world\HelloWorldTest.php`
- Execute the tests `php phpunit.phar hello-world\HelloWorldTest.php` and see the failure
- Make the tests pass
- Submit the solution `exercism submit .\hello-world\hello-world.php`
- Bask in the glory and exaltation of your peers
- Rinse and repeat
