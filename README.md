# Cloud-Based AI Data Analysis and Predictive Analytics System

A beginner-friendly STTP mini-project demonstrating a machine-learning workflow in Google Colab.

## Project workflow
1. Create and save a sample dataset.
2. Perform exploratory data analysis (EDA).
3. Preprocess the data and split it into training and test sets.
4. Train a Random Forest classifier.
5. Evaluate the model using accuracy, ROC-AUC, a classification report, and a confusion matrix.
6. Generate a sample prediction.

## Tools
- Python
- Google Colab / Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Run the project
1. Open Google Colab: https://colab.research.google.com/
2. Select **File → Upload notebook**.
3. Upload `Cloud_Based_AI_Predictive_Analytics.ipynb`.
4. Select **Runtime → Run all**.

The notebook creates a synthetic educational dataset, so no external dataset download is required.

## Cloud component
The notebook includes an optional Google Drive storage step. To demonstrate Google Cloud Storage (GCS), create a bucket in your own GCP project and upload the generated CSV using the Cloud Console. Never publish cloud credentials or service-account keys.

## Dataset and limitations
The dataset is generated synthetically with scikit-learn for demonstration. It is not real customer data and the model is not intended for real operational decisions.

## Suggested repository description
STTP mini-project demonstrating cloud-ready data processing, EDA, machine-learning model training, evaluation, and predictive analytics using Python and Google Colab.
