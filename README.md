# Titanic-Passenger-Mortality-Analysis-Project
This project analyzes factors affecting passenger mortality on the Titanic using Python and the libraries pandas, numpy, seaborn, and matplotlib.
---

## Project Goals
- Determine which factors (ticket class, cabin deck, age, number of relatives) influenced passenger survival.
- Visualize passenger distribution and mortality by age and family size.
- Categorize age groups and family size for more insightful analysis.

---

## Dataset
The dataset is loaded from the `seaborn` library:
```python
import seaborn as sns
df = sns.load_dataset('titanic')
