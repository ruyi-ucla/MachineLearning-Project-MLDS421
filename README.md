## MachineLearning-Project-MLDS421
Machine Learning Project for MLDS 421: Mashroom grouping with classification and clustering approaches
### Access to Data
```
pip install ucimlrepo 
from ucimlrepo import fetch_ucirepo 
secondary_mushroom = fetch_ucirepo(id=848) 
X = secondary_mushroom.data.features 
y = secondary_mushroom.data.targets 
```
