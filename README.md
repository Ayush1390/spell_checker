# Spelling Checker Project

This repository contains a Jupyter Notebook implementing a **spelling checker** that suggests corrections for misspelled words. The project uses various natural language processing techniques, including text preprocessing and probabilistic models, to identify and suggest likely corrections.

## Features
- **Word Splitting**: Breaks words into potential parts for analysis.
- **Word Deletion**: Removes characters to generate possible corrections.
- **Word Swapping**: Exchanges adjacent characters to correct common typos.
- **Word Replacement**: Replaces characters to find valid alternatives.
- **Word Insertion**: Adds characters to form valid words.

## Libraries Used
- **pandas**: For data handling and manipulation.
- **re**: For text preprocessing using regular expressions.
- **tqdm**: To display progress bars during operations.


## How It Works
1. **Text Preprocessing**: The input word is cleaned and prepared for analysis.
2. **Word Analysis**: The model generates potential corrections using various operations (split, delete, swap, replace, insert).
3. **Probability Calculation**: A probabilistic model is used to rank the suggested corrections based on their likelihood.
4. **Output**: The best suggestion is returned for the given input word.

## Examples
### Input:
```
exmple
```
### Output:
```
example
```

## Contributing
Contributions are welcome! Please create an issue or submit a pull request with your suggestions or improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

