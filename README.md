# Portuguese Bank Term Deposit Subscription
## Project Description
A Portuguese banking institution launched directed marketing campaigns to promote their products. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was
required, in order to access if the product (bank term deposit) would be subscribed or not. The dataset collected is related to 17 campaigns that occurred between May 2008 and November 2010,
corresponding to a total of 41,118 clients. For each client, a number of attributed was stored
and if there was a success (the target variable). For the project, 10,000 records are randomly allocated.
## Question of Interest
Based on the dataset, predict if the client will subscribe (yes/no) a term deposit (variable y).

## Target Variable
| Variable Name | Description |
|---------------|-------------|
| `y` | Indicates if the client subscribed to a term deposit (binary: `yes`, `no`). |

## Bank Client Data
| Variable Name | Description |
|---------------|-------------|
| `age` | Age of the client at the contact date. |
| `job` | Type of job (e.g., `admin.`, `blue-collar`, `entrepreneur`, `self-employed`, `services`, `student`, `technician`, `unemployed`). |
| `marital` | Marital status (`divorced`, `married`, `single`). **Note**: `divorced` includes widowed. |
| `education` | Education level (e.g., `basic.4y`, `basic.6y`, `basic.9y`, `high.school`, `illiterate`, `professional.course`, `university.degree`). |
| `default` | Has credit in default? (binary). |
| `housing` | Has a housing loan? (binary). |
| `loan` | Has a personal loan? (binary). |

## Last Contact Information
| Variable Name | Description |
|---------------|-------------|
| `contact` | Contact communication type (`cellular`, `telephone`). |
| `month` | Last contact month of the year (e.g., `jan`, `feb`). |
| `day_of_week` | Last contact day of the week (e.g., `mon`, `tue`). |
| `duration` | Last contact duration (seconds). **Important**: This attribute heavily affects the target variable (e.g., `duration=0` implies `y="no"`). **Note**: Duration is only known after the call and should be excluded for realistic predictive models. |

## Other Attributes
| Variable Name | Description |
|---------------|-------------|
| `campaign` | Number of contacts performed during this campaign for the client. |
| `pdays` | Number of days since the client was last contacted from a previous campaign. |
| `previous` | Number of contacts performed before this campaign for the client. |
| `poutcome` | Outcome of the previous marketing campaign (`failure`, `nonexistent`, `success`). |

## Social & Economic Context Attributes
| Variable Name | Description |
|---------------|-------------|
| `emp.var.rate` | Employment variation rate (quarterly indicator). |
| `cons.price.idx` | Consumer price index (monthly indicator). |
| `cons.conf.idx` | Consumer confidence index (monthly indicator). |
| `euribor3m` | Euribor 3-month rate (daily indicator). |
| `nr.employed` | Number of employees (quarterly indicator). |
