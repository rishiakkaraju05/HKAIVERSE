# AI-Assisted AI/ML Learning Exercises — Evidence Log

**Date prepared:** 24 October 2026  
**AI model used:** ChatGPT (GPT-6)

These five exercises focus on AI/ML concepts related to my B.Tech CSE (AI) coursework. The prompts and summaries document AI-assisted learning, while the verification notes distinguish calculations I checked from code or sources I still need to verify.

## Exercise 1 — Data preprocessing and data leakage

**Prompt**

> Explain data leakage in machine learning using a simple example. Give a safe order for splitting data, fitting preprocessing steps, and evaluating a model. Explain why a scaler must not be fitted on the full dataset before the train/test split.

**AI output (summary)**

Data leakage occurs when information that would not be available at prediction time influences model training or evaluation. If a scaler is fitted on the full dataset before splitting, information from the test set influences preprocessing. A safer workflow is to split first, fit preprocessing only on the training set, apply the fitted transformation to the test set, train the model, and evaluate on the untouched test set. A pipeline helps keep these steps in the correct order.

**Verification**

I checked the reasoning: the test set is meant to estimate performance on unseen data, so its information should not influence training or preprocessing.

**Status:** Conceptually reviewed. A scikit-learn code run and screenshot would provide additional practical evidence.

## Exercise 2 — Regression evaluation metrics

**Prompt**

> Explain MAE, MSE, RMSE, and R-squared. Use actual values `[3, 5, 7]` and predicted values `[2, 5, 9]` to calculate MAE, MSE, and RMSE step by step. Give one limitation of R-squared.

**AI output**

Errors are `[1, 0, -2]`; absolute errors are `[1, 0, 2]`.

- MAE = `(1+0+2)/3 = 1`
- MSE = `(1^2+0^2+(-2)^2)/3 = 5/3 ≈ 1.67`
- RMSE = `sqrt(5/3) ≈ 1.29`

MAE is the average absolute error in the target's units. MSE averages squared errors, penalizing larger errors more. RMSE is the square root of MSE and returns to the target's units. R-squared compares model predictions with a baseline that predicts the target mean, but a high R-squared alone does not prove good generalization.

**Verification**

I recalculated the absolute errors (1, 0, 2) and squared errors (1, 0, 4). Their averages are 1 and `5/3`, respectively, so RMSE is approximately 1.29.

**Status:** Arithmetic independently checked.

## Exercise 3 — Classification metrics and class imbalance

**Prompt**

> A classifier is evaluated on 100 samples: 40 are actually positive and 60 are actually negative. It correctly identifies 32 positive cases and 54 negative cases. Calculate TP, FN, TN, FP, accuracy, precision, and recall. Explain why accuracy alone may be insufficient.

**AI output**

- TP = 32
- FN = `40 − 32 = 8`
- TN = 54
- FP = `60 − 54 = 6`
- Accuracy = `(TP+TN)/100 = 86%`
- Precision = `TP/(TP+FP) = 32/38 ≈ 84.21%`
- Recall = `TP/(TP+FN) = 32/40 = 80%`

Accuracy alone can hide poor performance on a minority class. Precision and recall describe different kinds of errors, and the appropriate metric depends on the application.

**Verification**

I checked that `32+8=40` actual positives, `54+6=60` actual negatives, and all four confusion-matrix values sum to 100. The metrics recalculate to 86% accuracy, approximately 84.21% precision, and 80% recall.

**Status:** Counts and calculations independently checked.

## Exercise 4 — Overfitting and cross-validation

**Prompt**

> Explain overfitting in machine learning. Give an example where training accuracy is 99% but validation accuracy is 72%. Explain what this difference may indicate, how cross-validation helps, and why the test set should not be repeatedly used to choose a model.

**AI output (summary)**

Overfitting occurs when a model fits the training data too closely, including noise, and performs less well on unseen data. Training accuracy of 99% and validation accuracy of 72% suggests a generalization gap and possible overfitting, although the data split and evaluation setup should also be examined. Cross-validation estimates performance across multiple training/validation splits. The test set should be reserved for final evaluation; repeatedly selecting models based on test results leaks information into model selection.

**Verification**

I checked that the explanation distinguishes training performance from generalization and describes the purpose of cross-validation. The accuracy values are an illustrative example, not results from a model I trained.

**Status:** Conceptually reviewed; no model was trained for this example.

## Exercise 5 — Generative AI model families

**Prompt**

> Explain the basic idea behind variational autoencoders (VAEs), generative adversarial networks (GANs), and transformer-based generative models. For each, give one typical use and one limitation. Do not claim one family is always best.

**AI output (summary)**

- **VAE:** Learns a probabilistic latent representation and uses a decoder to generate samples. It can support representation learning and data generation. Depending on the objective, outputs may be blurrier than those from some other methods.
- **GAN:** Trains a generator and discriminator in competition. It can produce realistic-looking samples, but training may be unstable and may suffer from mode collapse, where outputs lack diversity.
- **Transformer-based generative models:** Use attention to learn relationships among tokens or sequence elements and generate outputs from context. They are widely used for text and other sequence generation, but can produce incorrect content, require substantial data and compute, and reflect training-data biases.

**Verification**

I checked that the summary distinguishes three different approaches instead of treating Generative AI as one model type. Before final submission, I should compare the summary with my course notes or an authoritative technical source and record the reference I actually use.

**Status:** Conceptual summary reviewed; source check still required.

## Reflection

These exercises focus on preventing data leakage, understanding regression metrics, evaluating classifiers, recognizing overfitting, and comparing generative model families. I independently recalculated the regression and classification metrics. The data-leakage and overfitting examples are conceptual; I have not claimed to have run code for them. The Generative AI summary still needs a source check.

## Evidence to save

- My own working for the regression and classification calculations.
- If possible, a scikit-learn example showing preprocessing fitted only on training data.
- If possible, a model comparison showing training versus validation performance.
- The course note or authoritative source I actually consult for VAE, GAN, and transformer-based models.
- Screenshots or outputs from any code I genuinely run, including corrections.
