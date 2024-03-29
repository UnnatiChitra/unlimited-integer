# Unlimited Integer

This C++ project provides a class, `unlimited_integer`, that can handle very large integers that are beyond the limit of standard integer types in C++. The class uses a string to store the integer value, allowing it to handle arbitrarily large numbers.

## Features

- Addition and subtraction operations for unlimited integers.
- Input and output stream operators for easy reading and writing of unlimited integers.
- A `print` method to display the value of an unlimited integer.

## Usage

Here is a simple example of how to use the `unlimited_integer class:

```cpp
#include "unlimited_integer.cpp"

int main() {
    unlimited_integer num1, num2;
    cout << "Enter two numbers: " << endl;
    cin >> num1 >> num2;
    unlimited_integer ans;
    ans = num1 - num2;
    cout << "The difference is: " << ans << endl;
    ans = num1 + num2;
    cout << "The sum is: " << ans << endl;
    return 0;
}
```

In this example, two unlimited integers are read from the input, their difference and sum are calculated, and the results are printed to the output.

## Files

- `unlimited_integer.cpp`: This file contains the implementation of the `unlimited_integer` class.

## License

This project is licensed under the terms of the license provided in the `LICENSE` file.

## Contributing

Contributions are welcome. Please submit a pull request or create an issue to discuss the changes you want to make.

## Contact

If you have any questions or comments about this project, please open an issue on GitHub.