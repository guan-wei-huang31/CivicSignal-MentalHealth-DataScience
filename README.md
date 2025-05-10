# CivicSignal - Public Service Data Science Project

## Project Overview

CivicSignal is a comprehensive data science project designed to provide data-driven insights into user segments, population needs, and behavioral patterns. Leveraging a combination of unsupervised learning (UMAP + HDBSCAN) and supervised learning (Decision Tree), this project offers a scalable, efficient workflow for optimizing public support services.

## Key Features

* **Unsupervised Learning:** Implements UMAP for dimensionality reduction and HDBSCAN for clustering user data.
* **Supervised Learning:** Utilizes a Decision Tree model for user classification, enabling the identification of key features influencing user behavior.
* **Advanced Data Analysis:** Provides actionable insights by identifying population needs and understanding behavioral patterns.
* **Scalable Workflow:** Supports the analysis of large-scale public service datasets.

## Technologies Used

### Data Preprocessing

* Data Cleaning: Deduplication, Filtering, and Missing Value Removal
* Data Transformation: Date-Time Parsing, Category Mapping, One-Hot Encoding, and Feature Engineering
* Data Integration: Merging and Concatenation of Features

### Core Technologies

* **Programming Language:** Python (3.x)
* **Libraries:**

  * NumPy
  * Pandas
  * Scikit-Learn
  * UMAP
  * HDBSCAN
  * Matplotlib

### Machine Learning Methodology

* **Unsupervised Learning:**

  * Applied UMAP for high-dimensional data visualization and dimensionality reduction.
  * Utilized HDBSCAN for robust clustering, effectively identifying distinct user segments.

* **Supervised Learning:**

  * Labeled clustered data using Decision Tree.
  * Optimized model for accuracy and feature importance analysis.
  * Visualized feature importance using a clear, intuitive bar chart.

## Installation and Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/CivicSignal.git
   ```

2. **Set Up a Python Environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Required Libraries:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Project:**

   * Open the Jupyter Notebook file.
   * Execute each cell in sequence to perform data analysis and model training.

## Project Structure

```
CivicSignal/
├── CivicSignal.ipynb    # Source code
├── requirements.txt     # Required libraries
└── README.md            # Project documentation
```

## Contact Me
Auther: Guan-Wei Huang (gwhuang24@gmial.com)

## License

© 2025 CivicSignal. All rights reserved.
Unauthorized use, reproduction, or distribution is prohibited without explicit permission.
