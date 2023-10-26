# Artist Social Network Web Application

## Introduction

This project is a web application that allows users to explore and visualize an artist social network. Users can select artists and see their connections in a graph format. The application also provides interactive features for exploring the network and visualizing various centrality measures. It's built using Flask, Bokeh, and Bootstrap to provide a user-friendly interface.

## Installation

Before running the application, make sure you have the required Python libraries installed. You can install them using the following command:

#### Required Libraries
See requirements.txt for the list of all python libraries
used for the implementation and execution of this project.

```bash
$ pip3 install -r requirements.txt

```bash

$ python3 -m flask run
```
   * ```gui``` directory contains the interface layer
   * ```applayer``` directory contains the logical layer for all interactions
   * ```datalayer``` directory contains the code for interfacing with data sources

## Architecture

### 3-Tier Architecture

This project follows a 3-tier architecture for modularity and separation of concerns:

1. **Interface Layer (gui):** This layer handles the user interface and interactions. It provides a user-friendly web interface for interacting with the artist social network.

2. **Logical Layer (applayer):** The logical layer contains the core functionality of the application. It processes user requests, computes centrality measures, and manages the social network's data.

3. **Data Layer (datalayer):** This layer interacts with data sources for artist information. It is responsible for retrieving and manipulating data related to artists and their relationships.


This command starts the web application, and you can access it through a web browser.

## Architecture

### 3-Tier Architecture

This project follows a 3-tier architecture for modularity and separation of concerns:

1. **Interface Layer (gui):** This layer handles the user interface and interactions. It provides a user-friendly web interface for interacting with the artist social network.

2. **Logical Layer (applayer):** The logical layer contains the core functionality of the application. It processes user requests, computes centrality measures, and manages the social network's data.

3. **Data Layer (datalayer):** This layer interacts with data sources for artist information. It is responsible for retrieving and manipulating data related to artists and their relationships.

### Architecture Diagram

The following diagram illustrates the relationships between these three tiers:

This architecture ensures that the project is well-organized and scalable. Each tier can be developed, tested, and scaled independently.

## License

This project is open-source and licensed under the [MIT License](LICENSE). You can find more details in the [LICENSE](LICENSE) file.

## Contact

If you have any questions or need further assistance, please contact us at [contact@email.com].

## Acknowledgments

We'd like to express our gratitude to the following libraries and tools that played a significant role in the development of this project:

- [Flask](https://flask.palletsprojects.com/)
- [Bokeh](https://docs.bokeh.org/en/latest/index.html)
- [Bootstrap](https://getbootstrap.com/)


