# ay2425-s2-pg13
ST5188 AY2024/25-S2 Project Group 13 Repository Resources

# 🛒 ST5188: Product Recommendation System using SBERT + FAISS

This repository contains the coursework project for ST5188, focusing on building a hybrid recommendation system for Instacart using multiple collaborative filtering techniques, BERT-based text embeddings, and FAISS for fast similarity search.

## 📁 Project Structure

├── data/                                        # Contains the Instacart dataset  
├── figure/                                      # Visualizations and generated plots  
├── results/                                     # Model checkpoints and output files  

├── 01-eda.ipynb                                 # Exploratory Data Analysis  
├── 02-feature.ipynb                             # Feature engineering and preprocessing  
├── 03-data analysis.ipynb                       # Detailed data analysis  
├── 04-lightfm.ipynb                             # Matrix Factorization using LightFM  
├── 05-ItemSimilarity_Recommendation.ipynb       # Item-based collaborative filtering  
├── 06-User-based CF for Instacart Recommendation.ipynb  # User-based collaborative filtering  
├── 07-Fine Tuned Sentence Bert+FAISS.ipynb      # BERT fine-tuning & FAISS index building  
├── 08-SBERT+FAISS evaluation.ipynb              # Evaluation of SBERT + FAISS model  

├── README.md                                    # Project documentation (this file)  
├── requirement.txt                              # Required Python packages  
├── .gitattributes                               # Git LFS configuration  


## 🧠 Key Components

### ✅ 1. Data Exploration
- `01-eda.ipynb` explores basic statistics, product frequency, and user behavior.

### ✅ 2. Feature Engineering
- `02-feature.ipynb` creates user-product interaction matrices and encodes metadata.

### ✅ 3. Recommendation Models

| Notebook | Method |
|----------|--------|
| `04-lightfm.ipynb` | Matrix Factorization using LightFM |
| `05-ItemSimilarity_Recommendation.ipynb` | Item-based Collaborative Filtering |
| `06-User-based CF for Instacart Recommendation.ipynb` | User-based CF |
| `07-Fine Tuned Sentence Bert+FAISS.ipynb` | Fine-tuned SBERT model + FAISS for fast retrieval |
| `08-SBERT+FAISS evaluation.ipynb` | Evaluation of semantic recommendations |

### ✅ 4. Outputs & Evaluation
- Results are saved under `results/`, including FAISS index, SBERT vectors, and fine-tuned models.

## 🧪 Installation

```bash
# Clone the repo
git clone https://github.com/your-repo/st5188-project.git
cd st5188-project

# Install dependencies
pip install -r requirement.txt

Please see the "Code Repository and Replication Instructions" part and APPENDIX in the report for detailed installation information.
