## Full Deep Learning Model Development Lifecycle
```
1. Problem Definition
2. Data Collection
3. Data Preprocessing / Feature Engineering
4. Dataset Splitting
      ├── Training Set
      ├── Validation Set
      └── Test Set
5. Model Architecture Design
6. Training Phase
      ├── Forward Propagation
      ├── Loss Computation
      ├── Backpropagation
      └── Gradient Descent (Optimization)
7. Validation / Model Tuning
8. Final Testing (Unseen Data)
9. Deployment
10. Monitoring & Retraining
```
## 📍 Where Gradient Descent Fits
```
                DATASET
                   │
        ┌──────────┼──────────┐
        │          │          │
     Train      Validation    Test
        │
        ▼
   Training Loop
        │
Forward → Loss → Backprop → Gradient Descent

```
