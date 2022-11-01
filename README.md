# Reynolds (Group 5)

## Team Members

Yulin Zhao (yulin6)
Siqi Du (siqidu3)
ShunTat Lam (stlam2)
Huiqian Jing (hjing6)

## Problem Statements

The group 5’s project aims to construct a neural network model to predict the gasoline price in the near future based on historical data, e.g. the next week. The network will intake government-issued chronological imports & outputs data of multiple types of oil and oil products from the 1980s to the 2020s as features, and gasoline prices as the label. The team hopes to use this model as an assistant tool in answering the increasing pressure of skyrocketing gas prices that American families are facing, by providing a reference for economic decisions. The team will also try to build a RNN model to predict the prices of future several weeks, providing further information for economic decisions.

## File System Explanation

Datasets:

- Datasets Folder
  - EMM_EPM0_PTE_NUS_DPGw.xlsx: the dataset contained prices
  - EMM_EPM0_PTE_NUS_DPGw.csv: the dataset contained prices
    - PET_MOVE_WKLY_DC_NUS-Z00_MBBLPD_W.xlsx: the dataset contained all features
    - PET_MOVE_WKLY_DC_NUS-Z00_MBBLPD_W_1.csv: the dataset contained the first part of features
    - PET_MOVE_WKLY_DC_NUS-Z00_MBBLPD_W_2.csv: the dataset contained the second part of features
    - PET_MOVE_WKLY_DC_NUS-Z00_MBBLPD_W_3.csv: the dataset contained the third part of features
- test_dataset.pkl: the debugging dataset (small)
- working_dataset.pkl: the working_dataset (complete, large)

Codes:

- ETL.ipynb: the notebook for data loading and cleaning.
- EDA.ipynb: the notebook for exploratary data analysis.
- baseline.ipynb: the notebook for the baseline performance (linear regression)

Others:

- readme.md: the documentation

## License:

MIT License

Copyright (c) [2022] [Reynolds]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
