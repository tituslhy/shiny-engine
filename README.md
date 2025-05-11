# shiny-engine

Ever think about experimenting with GraphRAG? This repository aims to be a simple guide to setup a GraphRAG application, and is a companion resource to an upcoming Medium publication.

## Here's what our full graph looks like
<p align="center">
    <img src="./images/full_kg.png">
</p>

## Here's a zoomed-in snippet of the graph
<p align="center">
    <img src="./images/full_kg_zoomed.png">
</p>

The main code can be found in `main_notebook.ipynb` on the root folder.

## Setup
Using poetry
```
poetry install
```

Using UV
```
pip install uv
uv sync
```

You need to have access to docker desktop or a Neo4j aura instance to use Neo4j!