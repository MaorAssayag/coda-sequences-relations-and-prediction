# Exploring Statistical Relations Between Coda Sequences of Dominica Sperm Whale Pairs

This notebook contains the full codebase, analysis, and results accompanying the research paper titled "Exploring Statistical Relations Between Coda Sequences of Dominica Sperm Whale Pairs". This project delves into the complex vocalizations of sperm whales, specifically analyzing the dependencies and predictability within their coda sequences during dyadic interactions.

<img src="assets/coda%20sequence%20alignment.png" alt="related coda sequence alignment" width="700"/>

<img src="https://img.icons8.com/bubbles/50/000000/information.png" style="height:50px;display:inline">

### Summary

---

This Python notebook includes:

* **Exploratory Data Analysis (EDA):** Comprehensive analysis of the sperm whale coda dataset.
* **Sequence Analysis:** Methods to process and analyze temporal relationships within coda sequences.
* **Statistical Tests:** Application of various statistical methods to uncover dependencies.
* **Machine Learning Models:**
    * Implementation, training, and evaluation of **Gaussian Mixture Model Hidden Markov Models (GMM-HMM)** for capturing probabilistic dependencies.
    * Implementation, training, and evaluation of **Long Short-Term Memory (LSTM) networks** for sequence prediction.
    * Implementation, training, and evaluation of **Transformer models** for advanced sequence modeling.
* **Visualization:** Interactive and static plots to illustrate data distributions, model performance, and key findings.

![Coda Features Symmetry](assets/coda%20features%20symmetry.png)

### Getting Started

To get started with this repository, clone it to your local machine and install the necessary dependencies.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/sperm-whale-coda-analysis.git](https://github.com/your-username/sperm-whale-coda-analysis.git)
    cd sperm-whale-coda-analysis
    ```
2.  **Create and activate a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: `venv\Scripts\activate`
    ```
3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt # A `requirements.txt` file listing all dependencies will be needed.
    ```
    *(Note: Please create a `requirements.txt` file in your repository listing all Python libraries used, e.g., numpy, pandas, scikit-learn, tensorflow/pytorch, matplotlib, seaborn, etc.)*

### Usage

The core of this project is presented in a Jupyter Notebook.

1.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
2.  Open the main notebook (`codaspred.ipynb`) and execute the cells sequentially to reproduce the analysis, model training, and results described in the paper.

### Paper Reference

For more details on the methodology, results, and discussion, please refer to the accompanying paper:

* **Exploring Statistical Relations Between Coda Sequences of Dominica Sperm Whale Pairs**
    * [URL will be updated]()

### License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) - see the `LICENSE` file for details.
