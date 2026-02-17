## Where does model risk governance / model risk management (MRM) fit into deep learning lifecycle?

## 🧭 1️⃣ First — What is Model Risk Governance?
**Definition (practical):**

A framework of policies, controls, validation, monitoring, and oversight to ensure models are:

* Accurate

* Explainable

* Compliant

* Stable

* Fair

* Fit-for-purpose

In banking, it aligns with regulatory guidance like SR 11-7, ECB TRIM, PRA, etc.

## 📍 2️⃣ Where It Fits in the Lifecycle

**Model risk governance** spans the entire model lifecycle, not just one stage.
## 🧱 Full Lifecycle With Governance Layer
```
1. Problem Definition
2. Data Collection
3. Data Preprocessing
4. Dataset Split (Train / Val / Test)
5. Model Design
6. Training (Gradient Descent runs here)
7. Validation / Tuning
8. Testing
9. Deployment
10. Monitoring
11. Retraining / Change Management

╔════════════════════════════════════╗
║   MODEL RISK GOVERNANCE LAYER      ║
╚════════════════════════════════════╝
   Covers ALL stages end-to-end


```
## 🔎 3️⃣ Stage-Wise Mapping
### 1️⃣ Problem Definition

#### Governance checks:

* Business justification

* Model materiality

* Risk tiering

* Regulatory impact

#### Artifacts:

* Model inventory entry

* Use case documentation

## 2️⃣ Data Governance

### Controls on:

* Data lineage

* Data quality

* Bias assessment

### PII compliance

* Sanctions/watchlist integrity

## 3️⃣ Model Development

*Covers:*

* Algorithm selection

* Feature engineering controls

* Explainability feasibility

* Documentation standards

*Gradient descent lives here but governance ensures:*

* Optimization is appropriate

* Loss function justified

* Convergence validated

## 4️⃣ Training & Validation

*Governance reviews:*

* Overfitting checks

* Stability tests

* Sensitivity analysis

* Hyperparameter justification

## 5️⃣ Independent Model Validation (IMV)

*Separate team performs:*

* Conceptual soundness review

* Mathematical verification

* Gradient/optimization review

* Reperformance testing

* They may re-run training independently.

## 6️⃣ Testing & Benchmarking

*Validation checks:*

* Out-of-sample performance

* Challenger models

* Stress testing

* Edge cases
  
## 7️⃣ Model Approval

* Governance bodies:*

* Model Risk Committee

* Model Validation Committee

* Approve or reject deployment.

## 8️⃣ Deployment Controls

* Includes:*

* Version control

* Access control

* Production monitoring hooks

## 9️⃣ Ongoing Monitoring

* Post-deployment governance monitors:*

* Data drift

* Concept drift

* Performance decay

* Bias emergence

## 🔟 Periodic Review / Retraining

*Triggers:*

* Performance drop

* Regulatory change

* Data shift

* Gradient descent runs again during retraining under governance oversight.

```
                 MODEL RISK GOVERNANCE
 ─────────────────────────────────────────────
 Problem Definition        │ Oversight
 Data                     │ Controls
 Model Design             │ Review
 Training (GD)            │ Validation
 Testing                  │ Challenge
 Deployment               │ Approval
 Monitoring               │ Surveillance
 Retraining (GD again)    │ Change control
 ─────────────────────────────────────────────

```
