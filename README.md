# GA_python_lab_data

A repository of files to be used with python lab materials.

For the college board lab use the following snippet to load all data frames
```python
import pandas as pd
act_2017 = pd.read_csv('https://raw.githubusercontent.com/plambson/GA_python_lab_data/main/college_board_files/act_2017.csv')
act_2018 = pd.read_csv('https://raw.githubusercontent.com/plambson/GA_python_lab_data/main/college_board_files/act_2018.csv')
act_2019 = pd.read_csv('https://raw.githubusercontent.com/plambson/GA_python_lab_data/main/college_board_files/act_2019.csv')
act_2019_ca = pd.read_csv('https://raw.githubusercontent.com/plambson/GA_python_lab_data/main/college_board_files/act_2019_ca.csv')
sat_2017 = pd.read_csv('https://raw.githubusercontent.com/plambson/GA_python_lab_data/main/college_board_files/sat_2017.csv')
sat_2018 = pd.read_csv('https://raw.githubusercontent.com/plambson/GA_python_lab_data/main/college_board_files/sat_2018.csv')
sat_2019 = pd.read_csv('https://raw.githubusercontent.com/plambson/GA_python_lab_data/main/college_board_files/sat_2019.csv')
sat_2019_by_intended_college_major = pd.read_csv('https://raw.githubusercontent.com/plambson/GA_python_lab_data/main/college_board_files/sat_2019_by_intended_college_major.csv')
sat_2019_ca = pd.read_csv('https://raw.githubusercontent.com/plambson/GA_python_lab_data/main/college_board_files/sat_2019_ca.csv')
sat_act_by_college = pd.read_csv('https://raw.githubusercontent.com/plambson/GA_python_lab_data/main/college_board_files/sat_act_by_college.csv')
```
For the terrorism lab use the following snippet to load all data frames
```python
import pandas as pd
plots = pd.read_csv('https://raw.githubusercontent.com/plambson/GA_python_lab_data/main/terrorism_files/plots.csv')
suspects = pd.read_csv('https://raw.githubusercontent.com/plambson/GA_python_lab_data/main/terrorism_files/suspects.csv')
```
