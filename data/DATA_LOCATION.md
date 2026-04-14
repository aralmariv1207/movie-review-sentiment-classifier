# Dataset Access

The primary dataset for this project exceeds GitHub's file size limit (**122.1 MB**). To ensure the analysis remains reproducible, the data is hosted externally.

### 🔗 Data Source
* **Download Link**: [Click here to access imdb_reviews.tsv on Google Drive](https://drive.google.com/drive/folders/1KlV0UeBl5X4G403gAy08faegVcmlHdTx?usp=drive_link)

### 📂 Dataset Details
* **Project**: Film Junky Union Sentiment Analysis
* **Format**: TSV (Tab-Separated Values)
* **Size**: 122.1 MB
* **Content**: 50,000+ IMDb movie reviews labeled for sentiment classification.

### ⚙️ Local Setup
To run the analysis locally:
1. Download the file from the link above.
2. Place it in the `/data` directory of this project.
3. Ensure your loading script specifies the tab separator: `pd.read_csv('imdb_reviews.tsv', sep='\t')`.
