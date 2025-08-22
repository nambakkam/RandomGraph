# RandomCustomGraph

RandomCustomGraph is a Qt-based application which plots some random data using QQuickPaintedItem and QPainter. The project is designed to run on both Windows and Ubuntu platforms.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Prerequisites

- Qt 5.15 or later installed on your system.
- C++ compiler compatible with Qt (e.g., GCC for Linux, MSVC for Windows).

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/RandomCustomGraph.git
    cd RandomCustomGraph
    ```

2. Build the project using Qt Creator or qmake:

    ```bash
    qmake
    make
    ```

    (For Windows, you may use Qt Creator or Visual Studio)

## Usage

1. Run the executable after building the project:

    ```bash
    ./RandomCustomGraph    # On Linux
    RandomCustomGraph.exe  # On Windows
    ```

2. The application will start and plot random values on the custom graph using QQuickPaintedItem.

## Contributing

We welcome contributions to RandomCustomGraph. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.
