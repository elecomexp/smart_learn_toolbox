
# Smart Learn Toolbox

**Smart Learn Toolbox** is a collection of functions and utilities designed to facilitate tasks in **Machine Learning**, **Data Science**, and **Deep Learning**. It includes a wide range of tools for preprocessing, modeling, visualization, and evaluation. 

## Disclaimer [⚠️] 

- Some functions may be duplicated or overlap in functionality.  
- Certain tools may be experimental, deprecated, or lack thorough testing.  
- Use with caution, especially in production environments.

## Features

- Utility functions for preprocessing datasets.
- Tools for model evaluation and metrics.
- Visualization helpers for both data analysis and model outputs.
- Deep learning components.

## Installation

Clone the repository to your local machine:
```bash
git clone https://github.com/elecomexp/smart_learn_toolbox.git
```

Add the directory to your Python project or use specific scripts as needed.

## Usage

The toolbox is modular, allowing you to import specific functionalities as needed. For example:

```python
from smart_learn_toolbox.datascience import get_cardinality
from smart_learn_toolbox.vizdatatools import plot_categorical_relationship

# Example usage
get_cardinality(df)
plot_categorical_relationship(df, cat_col1, cat_col2)
```
---

Smart Learn Toolbox is an ongoing project, so feedback and contributions are welcome. Happy coding!
