# 🛒 Product Recommendation for Walmart Products

This project builds a **content-based recommendation system** using product descriptions. It leverages **TF-IDF** and **cosine similarity** to suggest relevant products, improving customer experience and boosting conversions.

------------------------------------------------------------

📌 Problem Statement

- Vast Product Selection: Customers struggle to find relevant products in large catalogs.
- Need for Personalization: Tailored recommendations improve satisfaction and engagement.
- Improved Discovery & Conversion: Smart suggestions help users find what they need, faster.

------------------------------------------------------------

🔧 Methodology

- Data Preprocessing:
  - Remove duplicates, handle missing values
  - Extract and clean product descriptions
  - Standardize and transform text data

- TF-IDF Vectorization:
  - Converts product descriptions into numerical vectors
  - Highlights important words, ignores common/less-informative ones

- Cosine Similarity:
  - Measures similarity between product vectors
  - Products with highest similarity scores are recommended

------------------------------------------------------------

▶️ How to Run This Project in Google Colab

✅ Step 1: Open the Notebook

- Go to https://colab.research.google.com
- Upload your `.ipynb` notebook

✅ Step 2: Upload Files to Runtime

📁 Upload from Your Device:

- Click the folder icon on the left sidebar in Colab
- Click the Upload button
- Select and upload your data file (e.g., `products.csv`)
- Load it using:

```python
import pandas as pd
df = pd.read_csv('/content/products.csv')
```

🔗 Or Mount Google Drive:

```bash
from google.colab import drive
drive.mount('/content/drive')
df = pd.read_csv('/content/drive/MyDrive/path_to_file/products.csv')
```

✅ Step 3: Install Required Libraries (if needed)

```bash
!pip install pandas numpy scikit-learn
```

✅ Step 4: Run the Notebook

- Run all cells using Shift + Enter
- Input a product name and receive similar product recommendations based on description similarity

Input a product and receive similar product recommendations!
