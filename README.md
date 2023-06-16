# Learn Lerna Repository

This repository serves as a learning project for understanding and utilizing Lerna, a powerful tool for managing JavaScript projects with multiple packages.

## Getting Started

To get started with this project, please follow the steps below.

### Prerequisites

Before proceeding, ensure that you have the following software installed on your machine:

- Node.js (version X.X.X or higher)
- npm (version X.X.X or higher)
- Lerna (version X.X.X or higher)

### Installation

1. Clone this repository to your local machine by executing the following command:

   ```shell
   git clone <repository-url>
   
2. Navigate to the root directory of the repository:
   ```shell
   cd learn-lerna-repo

3. Install the project dependencies by running the following command:

    ```shell
    npm install

4. Bootstrap the packages using Lerna:

   ```shell
   lerna bootstrap


# Usage

The following commands are commonly used with Lerna:

    * lerna init - Initializes a new Lerna repository.
    * lerna create <package-name> - Creates a new package within the repository.
    * lerna add <package> [--dev] - Adds a dependency to one or more packages.
    * lerna run <script> - Executes a script in each package that contains it.
    * lerna exec <command> - Runs a command in each package.

For more detailed information on available commands and options, please refer to the Lerna documentation.


# Project Structure

This repository follows the Lerna monorepo structure. It consists of multiple packages located in the packages directory. Each package has its own package.json file and can be versioned independently.

The project structure is as follows:


   ```shell
learn-lerna-repo/
  |- packages/
      |- package1/
          |- src/
          |- package.json
      |- package2/
          |- src/
          |- package.json
  |- lerna.json
  |- package.json
  |- README.md

```
#  Contributing

Contributions to this repository are highly appreciated! If you encounter any issues or have ideas for new features, please feel free to open an issue or submit a pull request.

Before contributing, please take a moment to review our contribution guidelines for a smoother collaboration process.
License

This project is licensed under the MIT License.
   
```shell

Please remember to update any placeholders such as `<repository-url>` and versions to match your actual repository details. Additionally, if you have any specific sections or details you would like to include, feel free to let me know!
