# Employee Performance Analysis

HTML summary combining IT headcount metric and departmental distribution chart for executive workforce planning.

## Generated assets

- `analysis.html` &mdash; Stand-alone report embedding the histogram and key metrics.
- `department_histogram.png` &mdash; Histogram of employee counts per department.
- `employees.csv` &mdash; Synthetic dataset of 100 employees.
- `analysis.py` &mdash; Script that prints the IT frequency, produces the histogram, and writes the HTML report.

## Reproduce

```bash
python -m venv .venv
source .venv/bin/activate
pip install pandas seaborn matplotlib
python analysis.py
```

The script reports the IT department count to stdout and refreshes the HTML deliverable.

## Contact

23f2000340@ds.study.iitm.ac.in
