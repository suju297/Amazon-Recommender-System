# Recommender System for E-commerce (CS6140 Group 3)

Course project exploring recommender-system approaches on the Amazon Reviews 2023 dataset (`All_Beauty` subset), including:

- Collaborative Filtering (ALS / matrix factorization)
- Content-Based Filtering
- Neural Collaborative Filtering (NCF)

## Repository Structure

- `notebooks/` - Jupyter notebooks for each modeling approach
- `docs/` - final report, rough report draft, and presentation deck
- `data/` - placeholder directory for local/generated data (not committed)

## Notebooks

- `notebooks/CS6140 Group 3 Collaborative Filtering.ipynb`
- `notebooks/CS6140 Group 3 Content-based Filtering.ipynb`
- `notebooks/CS6140 Group 3 Neural Collaborative Filtering.ipynb`

## Setup (Local or Colab)

1. Create a Python environment (recommended Python 3.10+).
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebooks in Jupyter or Google Colab.

## Dataset

The notebooks load data from Hugging Face:

- `McAuley-Lab/Amazon-Reviews-2023`
- `raw_review_All_Beauty`
- `raw_meta_All_Beauty`

Some notebook cells assume Google Colab paths (for example `/content/...`) and may need path adjustments for local execution.

## Reported Results (from project report)

- Collaborative Filtering: RMSE `0.9023`, Precision@10 `0.1000`, Recall@10 `0.9500`
- Content-based Filtering: RMSE `0.9243`, Precision@10 `0.0947`, Recall@10 `0.5238`
- Neural Collaborative Filtering: RMSE `0.3993`, Precision@10 `0.2419`, Recall@10 `0.9671`

## Notes

- This repository was organized for source control after the project work was completed.
- Original project period: September 2024 to November 2024.

