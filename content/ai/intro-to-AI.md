---
title: "Introduction to AI"
date: 2024-03-26T22:43:45+05:30
draft: false
---
# Intelligence
Intelligence might be defined as the ability to learn
and perform suitable techniques to solve problems and
achieve goals, appropriate to the context in an uncertain,
ever-varying world. A fully pre-programmed factory robot
is flexible, accurate, and consistent but not intelligent.

# AI
Artificial intelligence (AI) is the theory and development of computer systems capable of tasks that historically required human intelligence such as perception, learning, reasoning, problem solving, language interaction, and even producing creative work.

## Types


![alt text](/ai/images/aitypes.png)


## Machine Learing
**Criteria**: whether system can learning incremtally from stream of data

| **Comparison**           | **Batch Learning**                                          | **Online Learning**                                        |
|--------------------------|-------------------------------------------------------------|-------------------------------------------------------------|
| **Data Processing**      | Processes data in fixed batches.                            | Adapts to incoming data points incrementally.               |
| **Memory Usage**         | Requires storing the entire dataset in memory.              | Doesn't require storing the entire dataset; memory-efficient.|
| **Computational Cost**   | High computational cost, especially for large datasets.    | Lower computational cost; updates are made incrementally.  |
| **Real-time Updates**    | Not suitable for real-time updates.                         | Supports real-time updates and rapid model adaptation.     |
| **Concept Drift**        | Less susceptible to concept drift as it trains on fixed data. | More susceptible to concept drift; requires monitoring.    |
| **Deployment**           | Slower deployment process due to batch processing.          | Faster deployment process; supports real-time applications.|
| **Scalability**          | Less scalable for large datasets due to memory constraints.| More scalable for large datasets and streaming data.       |

## Instance based VS Model Based
**criterion**: generalisation approach

| **Comparison**           | **Instance-based Learning**                               | **Model-based Learning**                                  |
|--------------------------|------------------------------------------------------------|------------------------------------------------------------|
| **Generalization**       | Memorizes training data, prone to overfitting.            | Generalizes with accurate models.                         |
| **Computational Complexity** | Expensive prediction.                                   | Training may be computationally intensive.                 |
| **Robustness**           | Robust to noise due to localized decision-making process, majority voting scheme, robust distance metrics, parameter tuning options, and the possibility of applying preprocessing techniques                                           | Sensitive to noisy data during training.                  |
| **Flexibility**          | Flexible to data distribution changes.                      | Flexibility depends on model complexity.                  |
| **Interpretability**     | Lacks interpretability.                                    | Some models like decision trees are interpretable.        |
| **Scalability**          | Becomes slow with large datasets.                          | Can handle large datasets efficiently with optimizations. |
| **Training Time**        | No explicit training phase; fast prediction.              | Training phase may be time-consuming.                     |
| **Prediction Time**      | Computationally expensive during prediction.              | Faster prediction.                                        |
| **Feature Importance**   | No explicit feature importance; relies on instance similarity. | Can provide feature importance insights.               |
| **Dimensionality**       | Performs well in high-dimensional spaces.                  | May struggle with high-dimensional data if data lack regularity                  |
Algorithm Examples | K-Nearest Neighbors (KNN), Case-Based Reasoning (CBR) | SVM, Decision Trees


Noise: random fluctuations or errors in the data that do not carry any meaningful information. 
Outliers: data points that deviate significantly from the rest of the dataset

### Self Supervised Learning

