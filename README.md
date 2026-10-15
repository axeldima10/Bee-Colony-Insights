# Bee Colony Insights

An interactive data-visualization project exploring how reported factors such as diseases and pesticides affect honey-bee colonies across U.S. states and years.

## Questions explored

- How does the reported percentage of impacted colonies vary by state?
- How do reported impacts change over time?
- How do the recorded impact categories compare across locations?

## Stack

Python, pandas, Plotly, Dash, and dash-bootstrap-components.

## Run locally

```bash
python -m venv .venv
# Activate the virtual environment, then:
pip install -r requirements.txt
python intro.py
```

Open the local URL printed by Dash in your browser.

## Files

- `intro.py`: Dash application
- `index.ipynb`: exploratory analysis
- `intro_bees.csv`: source dataset used by the app
- `index.html`: exported web view
- `newplot.png`: saved visualization

## Data note

The project uses a U.S. bee-colony dataset. Check the source dataset's metadata and definitions before interpreting trends; the visualizations are exploratory and do not establish causation.
