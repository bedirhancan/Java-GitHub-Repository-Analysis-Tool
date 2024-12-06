# Java-GitHub-Repository-Analysis-Tool

This Java console application allows users to analyze a GitHub repository by providing a repository URL. The tool performs various analyses on the Java files in the repository, including comment and code line statistics, and provides insights into the repository’s code quality.

## Features

- **Clone GitHub Repository**: Allows the user to provide a GitHub repository URL, which the tool then clones locally.
- **Extract Java Files**: Retrieves all `.java` files from the cloned repository.
- **Class Extraction**: Extracts files containing class definitions.
- **Code Analysis**: Analyzes each Java class and provides the following statistics:
  - **Javadoc Comment Lines**: Counts the number of Javadoc comment lines.
  - **Other Comment Lines**: Counts non-Javadoc comment lines.
  - **Code Lines**: Counts lines containing actual code (excluding comments and blank lines).
  - **LOC (Lines of Code)**: Calculates the total number of lines, including code and comments.
  - **Function Count**: Counts the total number of functions defined within the class.
  - **Comment Deviation Percentage**: Measures the percentage deviation of the comments required based on coding standards.

## Technologies Used

- **Java**: The application is built using Java to provide cross-platform functionality and flexibility.
- **GitHub API**: Used for cloning repositories and interacting with GitHub data.

## Setup & Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/bedirhancan/Java-GitHub-Repository-Analysis-Tool.git
    cd Java-GitHub-Repository-Analysis-Tool
    ```

2. Compile and run the Java application:
    ```bash
    javac Main.java
    java Main
    ```

3. When prompted, enter the GitHub repository URL you wish to analyze.

4. The application will automatically clone the repository, extract Java files, and perform the analysis.

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for more details.

## Author
- Bedirhan CAN
