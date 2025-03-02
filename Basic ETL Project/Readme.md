# Basic ETL Project

## Overview
This project demonstrates a basic ETL (Extract, Transform, Load) process. The goal is to extract data from a source, transform it according to business rules, and load it into a target data store.

## Project Structure
- `src/`: Contains the source code for the ETL process.
- `data/`: Directory for input and output data files.
- `docs/`: Documentation and resources related to the project.
- `tests/`: Unit tests for the ETL process.

## Data Flow
1. **Extract**: Read data from kaggle 
2. **Transform**: Clean and preprocess the data
3. **Load** : Into Sqllite 

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/basic-etl-project.git
    ```
2. Navigate to the project directory:
    ```sh
    cd basic-etl-project
    ```
3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. Place your input data files in the `data/input/` directory.
2. Run the ETL process:
    ```sh
    python src/main.py
    ```
3. The transformed data will be available in the `data/output/` directory.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For any questions or suggestions, please open an issue or contact the project maintainer at [thisispawanrajput@gmail.com].
