# Protein-Protein Interaction Network of Breast Cancer Genes

This project fetches protein interaction data from STRING for a small list of breast-cancer genes,
builds a network using NetworkX, and visualizes it.

How to run:
Create a new notebook.
Paste the code from ppi_network_analysis.ipynb.
Modify the genes list if desired.
Build the PPI network
Visualize and save the network graph

📂 Files in This Repository
ppi_network_analysis.ipynb → Main Jupyter/Colab notebook containing the code.

ppi_network.png → Saved PPI network image.

README.md → Project description and usage guide.

requirements.txt → List of required Python libraries (for local setup).

📊 Output Example
The analysis produces a network graph where:

Nodes represent proteins.

Edges represent known or predicted protein-protein interactions.

Thicker edges = higher confidence score from STRING.

📜 Data Source
STRING Database API
https://string-db.org
Species ID used in this example: 9606 (Homo sapiens).

🔮 Future Improvements
Allow dynamic input of gene lists from a text file or CSV.

Add functional enrichment analysis of the network proteins.

Integrate with Cytoscape for advanced visualization.

📧 Contact
Author: Eiman Meer
For any queries, suggestions, or collaborations, feel free to reach out.
