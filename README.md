# Graph Modeling Project

This project demonstrates graph modeling and visualization using NetworkX, Node2Vec, and PyVis. It creates a network of individuals and companies, generates node embeddings, and visualizes the graph structure and embeddings.

## Features

- Graph creation with NetworkX
- Node embeddings using Node2Vec and Word2Vec
- Interactive graph visualization with PyVis
- t-SNE visualization of node embeddings
- Score-based node coloring and tooltips

## Requirements

- Python 3.x
- NetworkX
- Node2Vec
- Gensim
- PyVis
- Matplotlib
- scikit-learn

## Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Open the Jupyter notebook:
```bash
jupyter notebook main.ipynb
```

2. Run the cells to generate the graph and visualizations.

## Project Structure

- `main.ipynb`: Main Jupyter notebook containing the graph modeling and visualization code
- `requirements.txt`: List of Python package dependencies
- `graph_visualization.html`: Generated visualization of the graph 