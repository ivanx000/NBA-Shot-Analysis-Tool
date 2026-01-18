# 🏀 NBA Shot Analyzer

> Decode professional shooting tendencies through recursive decision trees and interactive data visualization.

## 🎯 Overview

NBA Shot Analyzer is a Python-based data analysis tool that builds and visualizes decision trees from NBA shot log data. By processing high-fidelity player statistics from the 2014–2015 season, it identifies high-percentage scoring scenarios and visualizes a player’s "shot logic" through hierarchical trees and interactive charts.

### Key Features

- **🧠 Recursive Decision Trees**: Hierarchical mapping of shot outcomes based on player behavior.
- **📊 Predictive Analytics**: Calculates precise make/miss percentages for specific game scenarios.
- **📈 Interactive Visuals**: Browser-based pie charts powered by `mpld3` for shot distribution.
- **🔍 Strategic Insights**: Automatically identifies "Best-to-Take" and "Worst-to-Avoid" shot profiles.
- **📉 Graphviz Integration**: Generates clean, professional `.png` diagrams of the decision logic.

## 🏗️ Architecture

### Data Engine (Python)
- **Recursive Tree Builder**: Custom algorithm to categorize shots by Type, Touch Time, and Dribbles.
- **CSV Processing**: Efficient handling of NBA shot log datasets.
- **Python-TA**: Integrated code contract checking for high internal code quality.

### Visualization Stack
- **Graphviz**: For rendering complex hierarchical decision trees.
- **Matplotlib & mpld3**: For generating interactive, web-friendly statistical charts.
- **OS/Browser Integration**: Automated local hosting of data visualizations.

## 🚀 Getting Started

### Prerequisites

- Python 3.10+
- Graphviz (System-level installation required)
  - **macOS**: `brew install graphviz`
  - **Windows**: Download at [graphviz.org](https://graphviz.org/download/)

### Installation

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/nba-shot-analyzer.git
   cd nba-shot-analyzer
