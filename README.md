# Code

## Environment

* python  3.7
* torch  1.7.1
* transformers   4.10.1
* numpy 1.19.5

## Usage
   
   ```
   python main.py 
   ```

# Datasets
We have collected approximately one million patient-doctor conversations from online medical consultation platforms between 2022 and 2023. Each conversation includes a coarse-grained departmental label and a fine-grained pre-diagnosis disease tag. As a result, we have created two datasets: the Triage Dataset, which contains 407,060 samples with 14 categories, and the Pre-diagnosis Dataset, which consists of 344,883 samples with 48 categories. 

## Statistics for the Dataset

### Triage Dataset

| Department Name              | Data Quantity | Department Name       | Data Quantity |
| ---------------------------- | ------------- | --------------------- | ------------- |
| Obstetrics and Gynecology    | 113705        | Health Care           | 13848         |
| Internal Medicine            | 101906        | Mental Health         | 6037          |
| Traditional Chinese Medicine | 43281         | Plastic Surgery       | 5466          |
| Dermatology and Venereology  | 37086         | Beauty                | 4060          |
| Otolaryngology               | 30864         | Auxiliary Examination | 2783          |
| Surgery                      | 25443         | Infectious Diseases   | 1152          |
| Pediatrics                   | 20684         | Oncology              | 745           |

### Pre-diagnosis Dataset

| Department Name                                  | Data Quantity | Department Name                           | Data Quantity |
| ------------------------------------------------ | ------------- | ----------------------------------------- | ---- |
| Gynecology                                       | 39016         | Otolaryngology                            | 2179 |
| Traditional Chinese Medicine - Internal Medicine | 31045         | Hepatology                                | 1013 |
| Obstetrics                                       | 33524         | Depression                                | 660  |
| Respiratory Internal Medicine                    | 28204         | Hematology Internal Medicine              | 713  |
| Dermatology                                      | 33033         | Nephrology Internal Medicine              | 557  |
| Stomatology                                      | 17546         | Gynecological Oncology                    | 349  |
| Infertility                                      | 17285         | Thoracic Surgery                          | 227  |
| Endocrinology                                    | 16900         | Abdominal Tumors                          | 186  |
| Pediatrics - Internal Medicine                   | 19538         | Neurosurgery                              | 166  |
| Immunology                                       | 11741         | Weight Loss                               | 139  |
| Gastroenterology                                 | 13753         | Tuberculosis                              | 130  |
| Healthy Diet                                     | 9946          | Maternal and Child Health                 | 101  |
| Cardiology Internal Medicine                     | 10664         | Thoracic Tumors                           | 115  |
| Orthopedics                                      | 8227          | Dwarfism                                  | 110  |
| Urology                                          | 8075          | Pediatric Surgery                         | 105  |
| General Surgery                                  | 6911          | Scar Revision                             | 104  |
| Family Planning                                  | 6649          | Anxiety                                   | 90   |
| Plastic Surgery                                  | 4612          | Cosmetic Surgery                          | 87   |
| Insomnia                                         | 3901          | Hair Transplantation                      | 69   |
| Acne                                             | 4054          | Children's Nutrition and Development      | 66   |
| Ophthalmology                                    | 3735          | Pediatric Ophthalmology                   | 66   |
| Venereology                                      | 3411          | Environment and Health                    | 52   |
| Neurology Internal Medicine                      | 3418          | Traditional Chinese Medicine - Gynecology | 54   |
| Laboratory Tests                                 | 2304          | Schizophrenia                             | 53   |
### Statistics of the Triage and Pre-diagnosis datasets

| Datasets                | Triage  | Pre-diagnosis |
| ----------------------- | ------- | ------------- |
| # Number of categories  | 14      | 48            |
| # Trianing samples      | 325,647 | 275,905       |
| # Validation samples    | 40,706  | 34,488        |
| # Testing samples       | 40,707  | 34,490        |
| Average question length | 27.02   | 30.34         |
| Average answer length   | 124.61  | 127.44        |


