# Communication Network Analysis

This project explores the structure and dynamics of a communication network represented as a directed graph.

The dataset reflects message exchanges between participants involved in maritime operations, including vessel coordination, administrative procedures, monitoring activities and organizational communication.

The goal of the analysis is to understand how the network is structured, identify key actors, detect communities and explore the thematic content of messages.

---

## Project Objectives

- Transform graph-based data into a flat analytical structure
- Perform temporal analysis of communication activity
- Identify central and influential participants
- Detect structural communities within the network
- Analyze inter-cluster communication patterns
- Explore thematic patterns in message content

---

## Methodology

The analysis includes:

- Data preprocessing and graph transformation
- Time-based activity analysis
- Degree and betweenness centrality metrics
- Community detection using modularity optimization
- Inter-cluster interaction analysis
- Text mining and word frequency analysis

Python libraries used:

- pandas
- seaborn
- matplotlib
- networkx
- wordcloud
- scikit-learn

---

## Key Findings

- The network exhibits a moderately centralized structure
- A dense core of highly connected participants is present
- Several stable communities were detected
- Communication is predominantly intra-cluster
- Certain actors act as bridges between communities
- Message content is largely operational and coordination-focused

---

## Visualizations

The project includes:

- Temporal activity plots
- Sender and receiver activity rankings
- Network graph visualization
- Community detection visualization
- Inter-cluster heatmap
- Word clouds and content analysis plots

---

## Repository Structure

```
communication-network-analysis/
│
├── network_analysis.ipynb
├── data/
├── images/
└── README.md
```

---

## How to Run

1. Clone the repository
2. Install required dependencies
3. Open the notebook `network_analysis.ipynb`
4. Run all cells sequentially

---

## Author

Student project – network analysis and data visualization
