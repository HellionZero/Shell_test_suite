# Minishell Test Suite

*Test suite for validating the functionality of the Minishell Project. by HellionZero*

This repository contains a test suite for the Minishell project, designed to validate the functionality and robustness of your shell implementation. The tests cover various aspects of shell behavior, including command execution, built-in commands, environment variable handling, and error handling.

## Test Structure

The test suite is organized into several categories, each focusing on specific features of the Minishell:

1. **Command Execution Tests**: These tests verify that the shell can execute basic commands, handle arguments correctly, and manage input/output redirection.

2. **Built-in Command Tests**: This category includes tests for built-in commands such as `cd`, `echo`, `export`, and `unset`, ensuring they function as expected.

3. **Environment Variable Tests**: These tests check the shell's ability to manage environment variables, including setting, unsetting, and retrieving variable values.

4. **Error Handling Tests**: This section includes tests that intentionally trigger errors to ensure the shell responds appropriately, such as handling invalid commands or syntax errors.

## Running the Tests

To run the tests, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/HellionZero/Shell_test_suite.git
   ```

2. Navigate to the test suite directory:
   ```bash
   cd minishell-test-suite

3. execute the test script:
   ```bash
   ./run_all_tests.sh
   ```
if you want to run specific tests, you can execute individual test scripts located in the `tests` directory.

to know more about the usage of the test suite, please check also the my minishell repository, where you can find a detailed explanation of the test suite and how to use it effectively.
visit https://github.com/HellionZero/my_first_shell to see the test suite in action and to understand how to integrate it with your own Minishell implementation.

## Contributing

Contributions to the test suite are welcome! If you have additional tests or improvements to suggest, please feel free to submit a pull request. Make sure to follow the existing test structure and provide clear descriptions for any new tests you add.