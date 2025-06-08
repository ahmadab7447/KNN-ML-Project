
# 📊 K-Means Clustering on Social Media Live Metrics

This machine learning project applies **K-Means Clustering** to uncover hidden patterns in a dataset of live social media metrics. The goal is to segment social media posts/pages into distinct groups based on performance indicators such as reach, engagement, and page views.

---

## 📌 Objective

To use **unsupervised learning** (K-Means Clustering) to:
- Group similar social media posts or pages
- Identify performance-based clusters
- Assist marketers in tailoring content strategies

---

## 🧾 Dataset Description

**File**: `Live.csv`

The dataset contains metrics related to social media posts/pages. Key features include:

- `status_id`: Unique ID of the post
- `status_type`: Type of post (e.g., video, photo, link)
- `num_reactions`, `num_comments`, `num_shares`: Engagement indicators
- `total_reach`, `page_engaged_users`, `page_consumptions`: Page performance metrics

---

## 🧠 Machine Learning Algorithm

- **Algorithm Used**: K-Means Clustering
- **Library**: `scikit-learn`

---

## 🛠 Technologies Used

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn (for data visualization)
- Jupyter Notebook

---

## 🔍 Workflow

1. **Load and Explore Dataset**
   - Inspect missing values
   - Data overview and statistics

2. **Data Cleaning**
   - Handle missing/null values
   - Drop unnecessary columns (e.g., `status_id`)

3. **Feature Selection & Scaling**
   - Select relevant numerical features
   - Apply `StandardScaler` for normalization

4. **K-Means Clustering**
   - Determine optimal number of clusters using the Elbow Method
   - Fit the K-Means model
   - Assign cluster labels

5. **Cluster Visualization**
   - Use PCA or selected feature pairs for 2D visualization
   - Analyze characteristics of each cluster

---

## 📦 How to Run

```bash
# Step 1: Clone the repository
git clone https://github.com/yourusername/kmeans-socialmedia-clustering.git
cd kmeans-socialmedia-clustering

# Step 2: Install required libraries
pip install -r requirements.txt

# Step 3: Run the Jupyter Notebook
jupyter notebook kmeans_clustering.ipynb

















































































