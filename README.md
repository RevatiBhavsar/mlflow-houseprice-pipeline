
# 🏗️ From ML Project to Data Science: Building Workflows That Actually Scale

This repository demonstrates how to take a simple machine learning model and turn it into a **production-ready ML workflow** using **ZenML**, **MLflow**, and **modular design patterns**. The project uses the [Ames Housing dataset](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset) to predict house prices, but the focus is on **workflow thinking** and **MLOps best practices**—not just accuracy.

> 📘 [Read the full Medium article](https://medium.com/@revati.bhavsar/from-ml-project-to-data-science-building-workflows-that-actually-scale-3235ce8cf10d)

## 🚀 Key Concepts Demonstrated

-  **Modular Pipelines** with [ZenML](https://zenml.io/)
-  **Reusable Design Patterns** (Factory, Strategy, Template)
-  **MLflow** for experiment tracking and model registry
-  Clean separation of ingestion, preprocessing, training, evaluation, and deployment
-  CI/CD and MLOps-ready structure

## 📁 Project Structure

```
.
├── analysis/              # EDA modules (univariate, bivariate, etc.)
├── data/                  # Input and output datasets
├── explanations/          # Demo files for design patterns
├── extracted_data/        # Cleaned output from data ingestion
├── mlruns/                # MLflow metadata
├── pipelines/             # ZenML pipeline definitions
├── src/                   # Utility functions and helper classes
├── steps/                 # Modular ZenML pipeline steps
├── config.yaml            # Runtime configuration
├── requirements.txt       # Python dependencies
├── run_pipeline.py        # Training pipeline entrypoint
├── run_deployment.py      # Deployment pipeline entrypoint
└── sample_predict.py      # Batch inference script
```

## 🧪 How to Run Locally

1. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

2. **Initialize ZenML**  
   ```bash
   zenml init
   ```

3. **Run the full training pipeline**  
   ```bash
   python run_pipeline.py
   ```

4. **Deploy the model**  
   ```bash
   python run_deployment.py
   ```

5. **Run batch inference**  
   ```bash
   python sample_predict.py
   ```

## 🧠 What You’ll Learn

This project is ideal for:
- Aspiring **data scientists** who want to transition from notebooks to scalable workflows
- **MLOps enthusiasts** looking to build reproducible and modular ML systems
- Engineers who want to **apply software design patterns** to data pipelines


## 🙋‍♀️ Author

**Revati Bhavsar**  
[LinkedIn](https://linkedin.com/in/revatibhavsar) | [Medium](https://medium.com/@revati.bhavsar) | [GitHub](https://github.com/RevatiBhavsar)

## ⭐️ If you find this helpful…

- Drop a ⭐️ on this repo  
- Share the [Medium article](https://medium.com/@revati.bhavsar/from-ml-project-to-data-science-building-workflows-that-actually-scale-3235ce8cf10d)  
- Reach out for collaborations or hiring discussions!
