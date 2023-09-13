# Perceptron with Pocket Algorithm

![].(pic.png)

This Python program implements the Perceptron algorithm using the Pocket Algorithm. It is used for binary classification and finding a linear separator that separates two classes of data points. The Pocket Algorithm is employed to find the best linear separator that minimizes the number of misclassifications.

## Dependencies

This program uses the following Python libraries:

- pandas
- numpy
- matplotlib

## Functions

### `perceptron_pocket(x_data, y_data, number_of_iteration=300, alpha=0.005)`

This function implements the Perceptron algorithm with the Pocket Algorithm to find the best linear separator.

- `x_data`: Feature data as a NumPy array or DataFrame.
- `y_data`: Target labels as a NumPy array or DataFrame.
- `number_of_iteration`: The maximum number of iterations (default: 300).
- `alpha`: Learning rate (default: 0.005).

The function returns the best weights and bias that minimize misclassifications.

### `miss_calc(x_test, y_test, weights, bias)`

This function calculates the count of misclassifications on test data using the provided weights and bias.

- `x_test`: Feature data for testing as a NumPy array or DataFrame.
- `y_test`: Target labels for testing as a NumPy array or DataFrame.
- `weights`: Weights obtained from training.
- `bias`: Bias obtained from training.
