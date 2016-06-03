# PHP Code Exercises

The following code exercises are available for the PHP track. You are encouraged to complete these as you progress through the coursework.

## Excercises
- Introductory Exercise
    - ["Hello, Code Louisville!"](https://github.com/CodeLouisville/php-exercise-hello-code-louisville)
- Basic Exercises
    - [Data Types in PHP](https://github.com/CodeLouisville/php-exercise-data-types)
    - [String Search](https://github.com/CodeLouisville/php-exercise-string-search)
    - [Date Formatter](https://github.com/CodeLouisville/php-exercise-date-formatter)
    - [Odd Numbers](https://github.com/CodeLouisville/php-exercise-odd-numbers)
    - [Array Histogram](https://github.com/CodeLouisville/php-exercise-array-histogram)
    - [`array_keys()`++](https://github.com/CodeLouisville/php-exercise-array-search-keys)
- Object Oriented Exercises
    - [PHP OOP](https://github.com/CodeLouisville/php-exercise-oop)

## Getting Started
To perform a code exercise, [fork](https://help.github.com/articles/fork-a-repo/) one of the repositories above. Follow the exercise `README.md` and make your code changes in the `src/` directory.

## Submitting Your Solution
When you are done, commit and push your changes to your fork and [create a pull request](https://help.github.com/articles/creating-a-pull-request/). Upon doing so your solution will be automatically tested.

If your solution passes, the build will be marked successful and the pull request will be ready to merge.

If your solution fails, the build will be marked as failing and the pull request can no be merged. You should receive an email with more information about the failure. Make your changes. Once you commit them, the pull request will automatically be updated and the tests will rerun.

## Running Tests Locally
While it works, submitting a pull request to test your solution is time consuming and unnecssary. As such, you should run the tests locally before creating a pull request. This will also help familiarize you with the command line and using [Composer](https://getcomposer.org/doc/00-intro.md).

To do so:

1. Open a terminal
2. Navigate to the project's root directory, e.g. `cd /workspace/dir/php-code-challenge`
3. Install the project dependencies by running `composer install`. **Note:** this only needs to be done once. 
4. Run the tests with: `vendor/bin/phpunit`
