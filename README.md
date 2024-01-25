# Data Analysis Tool

This Go program reads data from a file, performs linear regression analysis, and calculates the Pearson correlation coefficient. It uses the `readDataFromFile` function to read data from the file and return it as a slice of float64 values. The `linearRegression` function calculates the slope and intercept of the linear regression line, while the `pearsonCorrelation` function calculates the Pearson correlation coefficient. Finally, the program prints the results.

## Usage

To use this code, follow the steps below:

1. Ensure that you have Go installed on your system.

2. Save the code in a file with a `.go` extension, for example, `main.go`.

3. Open a terminal or command prompt and navigate to the directory where the file is saved.

4. Run the code by executing the following command:

   ```shell
   go run main.go <file_path>
   ```

   Replace `<file_path>` with the path to the file containing the data you want to analyze.

## Dependencies

This code has the following dependencies:

- `bufio` package: Used for reading data from a file.
- `fmt` package: Used for printing the results.
- `log` package: Used for error logging.
- `math` package: Used for mathematical calculations.
- `os` package: Used for command-line arguments and file operations.
- `strconv` package: Used for converting string values to float64.

The code uses the standard library packages, so there is no need to install any additional dependencies.

## Functionality

The code performs the following tasks:

1. Reads data from a file specified as a command-line argument.

2. Calculates the linear regression line using the provided data.

3. Calculates the Pearson correlation coefficient using the provided data.

4. Prints the linear regression line and the Pearson correlation coefficient.

## File Reading

The code reads data from a file using the `readDataFromFile` function. This function takes a file path as a parameter and returns a slice of `float64` values representing the data read from the file.

## Linear Regression

The code calculates the linear regression line using the provided data. The `linearRegression` function takes a slice of `float64` values as input and returns the slope and intercept of the regression line.

## Pearson Correlation Coefficient

The code calculates the Pearson correlation coefficient using the provided data. The `pearsonCorrelation` function takes a slice of `float64` values as input and returns the correlation coefficient.

## Output

The code prints the following results:

- The linear regression line in the format: `y = <slope>x + <intercept>`.
- The Pearson correlation coefficient with 10 decimal places.

Please ensure that you provide a valid file path as a command-line argument when running the code.
