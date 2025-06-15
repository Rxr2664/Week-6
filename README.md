# Week-6


# NFL Data Processing Assignment

This project demonstrates a basic data ingestion and validation pipeline using NFL prediction data. It showcases how to:
- Ingest a CSV file using Pandas, Modin, and Dask
- Clean column names
- Generate and validate a YAML schema
- Output the result in pipe-separated `.gz` format
- Summarize the dataset (row/column count, file size)

## 📂 Files Included
| File                        | Description                                |
|-----------------------------|--------------------------------------------|
| `nfl_predictions.csv`       | Simulated NFL predictions input data       |
| `output_cleaned.txt.gz`     | Final cleaned + compressed output file     |
| `schema.yaml`               | Schema with separator + column list        |
| `nfl_processing.ipynb`      | Full Colab notebook with all code          |
| `README.md`                 | This project overview                      |

## ✅ Tools Used
- Python (Pandas, Modin, Dask)
- YAML
- Google Colab

## 📊 Output Summary
- Rows: 5  
- Columns: 6  
- Format: pipe-separated `.gz`

---

*Created by [Your Name]*
