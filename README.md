# UCI_Bank_Marketing_ML

Data Source: https://archive.ics.uci.edu/ml/datasets/bank+marketing

## Bank Marketing Data (A Data-Driven Approach to Predict the Success of Bank Telemarketing.)
### Data Set Information:

The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

### There are four datasets:
1) bank-additional-full.csv with all examples (41188) and 20 inputs, ordered by date (from May 2008 to November 2010), very close to the data analyzed in [Moro et al., 2014]
2) bank-additional.csv with 10% of the examples (4119), randomly selected from 1), and 20 inputs.
3) bank-full.csv with all examples and 17 inputs, ordered by date (older version of this dataset with less inputs).
4) bank.csv with 10% of the examples and 17 inputs, randomly selected from 3 (older version of this dataset with less inputs). The smallest datasets are provided to test more computationally demanding machine learning algorithms (e.g., SVM).

The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).

### Attribute Information:

### Input variables:

### Bank client data:
1 - age (numeric)
2 - job : type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')
3 - marital : marital status (categorical: 'divorced','married','single')
4 - education (categorical: 'unknown','primary','secondary','tertiary')
5 - default: has credit in default? (categorical: 'no','yes')
6 - housing: has housing loan? (categorical: 'no','yes')
7 - loan: has personal loan? (categorical: 'no','yes')
8 - balance: account balance (numeric)

### Related with the last contact of the current campaign:
9 - contact: contact communication type (categorical: 'cellular','telephone','unknown')
10 - day: last contact day of the month(numeric: 1,2,...,31)
11 - month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
12 - duration: last contact duration, in seconds (numeric).

### Other attributes:
13 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
14 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; -1 means client was not previously contacted)
15 - previous: number of contacts performed before this campaign and for this client (numeric)
16 - poutcome: outcome of the previous marketing campaign (categorical: 'failure','other','success','unknown')

<img src="https://github.com/YingluDeng/UCI_Bank_Marketing_ML/blob/main/Slide_pic/Screen%20Shot%202022-01-18%20at%209.37.55%20PM.png" />
<img src="https://github.com/YingluDeng/UCI_Bank_Marketing_ML/blob/main/Slide_pic/Screen%20Shot%202022-01-18%20at%209.38.02%20PM.png" />
<img src="https://github.com/YingluDeng/UCI_Bank_Marketing_ML/blob/main/Slide_pic/Screen%20Shot%202022-01-18%20at%209.38.11%20PM.png" />
<img src="https://github.com/YingluDeng/UCI_Bank_Marketing_ML/blob/main/Slide_pic/Screen%20Shot%202022-01-18%20at%209.38.21%20PM.png" />
<img src="https://github.com/YingluDeng/UCI_Bank_Marketing_ML/blob/main/Slide_pic/Screen%20Shot%202022-01-18%20at%209.39.19%20PM.png" />
<img src="https://github.com/YingluDeng/UCI_Bank_Marketing_ML/blob/main/Slide_pic/Screen%20Shot%202022-01-18%20at%209.39.26%20PM.png" />
<img src="https://github.com/YingluDeng/UCI_Bank_Marketing_ML/blob/main/Slide_pic/Screen%20Shot%202022-01-18%20at%209.39.35%20PM.png" />
<img src="https://github.com/YingluDeng/UCI_Bank_Marketing_ML/blob/main/Slide_pic/Screen%20Shot%202022-01-18%20at%209.39.42%20PM.png" />
