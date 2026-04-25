# From Environmental Language to Speculative 3D Fragments

This repository contains the code, datasets, generated maps, plots, and design workflow materials for my DfPI Digital Skills project.

## Project Overview

This project explores how environmental language can be translated into speculative three-dimensional form. I started from public text datasets and treated language as design material.

The workflow moves from web scraping and text analysis to image transformation, 3D fragment generation, and final animation. The project combines Python, machine learning, API-based semantic translation, TouchDesigner, and Blender in one continuous process.

## Workflow

Web scraping  
→ cleaning and dataset preparation  
→ TF-IDF and sentence embedding comparison  
→ K-means clustering  
→ API-based semantic translation  
→ Python grayscale map generation  
→ TouchDesigner map processing  
→ Blender fragment generation  
→ final animation

## Datasets

Three text datasets were collected from two public domains:

1. **Wikipedia landforms**  
   Used to capture spatial structure and geological language.

2. **Wikipedia climate and environmental processes**  
   Used to capture dynamics such as erosion, weathering, and environmental change.

3. **Project Gutenberg nature writing**  
   Used to introduce atmospheric and descriptive language.

## Methods

### Vectorisation
Two vectorisation methods were compared:
- TF-IDF
- Sentence embeddings

TF-IDF was used for keyword interpretation, while sentence embeddings were used for clustering because they produced stronger semantic grouping.

### Machine Learning
K-means clustering was applied to the sentence embeddings in order to identify recurring semantic groups.

### API Translation
The API was used as a semantic translation layer. Clustered text was translated into structured design parameters such as:
- openness
- verticality
- roughness
- density
- motion intensity
- fragmentation
- surface continuity

It also generated prompts for image processing and fragment development.

## Design Tool Integration

### Python
Used for scraping, cleaning, vectorisation, clustering, visualisation, and grayscale map generation.

### TouchDesigner
Used to transform grayscale maps into refined height-like, mask-like, and texture-like outputs through TOP-based image processing.

### Blender
Used to translate 2D maps into 3D fragments through displacement and solidify operations, and to produce the final animation.

## Final Outputs

The final output includes:
- 3 text datasets
- vectorisation comparison
- K-means cluster analysis
- API-generated design parameters
- Python-generated grayscale maps
- TouchDesigner processed maps
- 21 speculative architectural fragments
- a 1-minute animation

## Repository Structure

- `notebooks/` — Jupyter notebooks for scraping, cleaning, vectorisation, clustering, and API translation  
- `data/cleaned/` — cleaned text datasets  
- `data/processed/` — clustered and processed outputs  
- `data/api_outputs/` — API-generated JSON and CSV outputs  
- `outputs/plots/` — clustering and analysis visualisations  
- `outputs/maps/` — Python-generated maps  
- `outputs/maps_td/` — TouchDesigner processed maps  
- `touchdesigner/` — TouchDesigner project files  
- `blender/` — Blender project files

- ## Public links
OneDrive folder: [https://liveuclac-my.sharepoint.com/:f:/g/personal/ucbvyg8_ucl_ac_uk/IgAf0WJNZE5UTqVwGcQ1cr4RASQDy34Sr5S06TLwLHEHQCo?e=2UH0Vz]
Final animation: [https://liveuclac-my.sharepoint.com/:v:/g/personal/ucbvyg8_ucl_ac_uk/IQBh7tBA9y3HSb8q87tkUEGlAagxEj5XxzFtwS6VNUrP_nw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=yyhn1s]


## Credits

Data sources:
- Wikipedia
- Project Gutenberg

Python libraries:
- pandas
- scikit-learn
- sentence-transformers
- matplotlib
- seaborn
- Pillow

Software:
- TouchDesigner
- Blender

API:
- OpenAI API

Additional support:
- ChatGPT was used as a workflow and writing support tool.
