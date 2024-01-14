# Community Detection in Dynamic Networks

## Overview

This repository contains code and analysis for detecting communities in dynamic networks using network analysis techniques. The primary focus is on identifying and visualizing communities within different aspects of the data, such as groups of attackers, attack types, target types, and weapon types.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Methods](#methods)
- [Results](#results)
- [Community Detection](#community-detection)
- [Graph Visualization](#graph-visualization)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Dynamic networks play a crucial role in understanding complex systems and relationships. This project focuses on analyzing and detecting communities within different attributes of a dynamic network dataset related to global terrorism. The repository provides code for exploring communities among terrorist groups, attack types, target types, and weapon types.

## Installation

To run the code locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your-username/community-detection-dynamic-networks.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

The main code is organized into Jupyter Notebooks for each aspect of community detection. You can run the notebooks to analyze and visualize communities within the dynamic network.

```bash
jupyter notebook
```

## Data

The dataset used for this project is sourced from [Global Terrorism Database](https://www.start.umd.edu/gtd/). It provides information on terrorist attacks worldwide, including details on attackers, targets, attack types, and more.

## Methods

The analysis employs various network analysis techniques, including Louvain community detection algorithm, degree centrality, betweenness centrality, and eigenvector centrality. These methods help in identifying groups and influential nodes within the dynamic network.

## Results

The results of the analysis are presented in the Jupyter Notebooks along with visualizations. The findings include insights into community structures, influential nodes, and dynamic changes over time.

## Community Detection

The community detection aspect of the project focuses on partitioning the network into groups based on shared characteristics. Louvain community detection is used to identify these communities within different attributes.

## Graph Visualization

Graph visualizations are included to illustrate the structure of communities, connections, and changes over time. These visualizations are crucial for understanding the dynamics within the network.

## Conclusion

The project concludes with a summary of findings, insights gained, and potential use cases for leveraging community detection in dynamic networks.

![image](https://user-images.githubusercontent.com/43510001/194229600-bc71c1ca-1f06-4cbb-9767-c924a6386737.png)

## Contributing

Contributions to the project are welcome. If you have suggestions, improvements, or want to report issues, please create a pull request or submit an issue.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this README template based on additional details and specifics of your project.
