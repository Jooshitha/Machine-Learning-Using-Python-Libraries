# Find-S algorithm for the given training dataset

For a given set of training data examples stored in a .CSV file, this program will  implement and demonstrate the Find-S algorithm to output a description of the set of all hypotheses consistent with the training examples.

## Features

- Reads training data from a CSV file
- Implements the Find-S algorithm to learn the most specific hypothesis
- Prints the training data and the final hypothesis

## Output

|   | Outlook   | Temperature | Humidity | Windy | PlayTennis |
|---|-----------|-------------|----------|-------|------------|
| 0 | Sunny     | Hot         | High     | False | No         |
| 1 | Sunny     | Hot         | High     | True  | No         |
| 2 | Overcast  | Hot         | High     | False | Yes        |
| 3 | Rain      | Cold        | High     | False | Yes        |
| 4 | Rain      | Cold        | High     | True  | No         |
| 5 | Overcast  | Hot         | High     | True  | Yes        |
| 6 | Sunny     | Hot         | High     | False | No         |

**The final hypothesis is:** `['Overcast', 'Hot', 'High', '?']`