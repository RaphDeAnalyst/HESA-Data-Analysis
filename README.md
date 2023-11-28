# HESA-Analysis
## Introduction
This project utilizes datasets from the official [HESA](https://www.hesa.ac.uk/) website, focusing on three key datasets: [HE student enrolments by domicile and region of HE provider](https://www.hesa.ac.uk/data-and-analysis/students/table-11), [HE student enrolments by personal characteristics](https://www.hesa.ac.uk/data-and-analysis/sb265/figure-5), and [HE student enrolments by level of study](https://www.hesa.ac.uk/data-and-analysis/sb265/figure-3). The analysis covers data spanning from the 2017/18 to 2021/22 academic sessions.

### This project aims to:

1. Analyze domicile and regional trends in HE student admissions in the UK over five academic sessions (2017/18–2021/22).
2. Investigate the impact of personal characteristics (age group, sex, disability, religious belief) on HE student enrollment.
3. Compare the enrollment numbers for undergraduate and postgraduate HE students.

## Methodology:

### Data Preprocessing:
The data underwent preprocessing and transformation using Power Query. Columns containing session information were unpivoted into rows, and tables for each session were appended.
![Screenshot (56)](https://github.com/RaphDeAnalyst/HESA-Analysis/assets/76891015/4637cdf8-b077-4280-8874-113e4b9c7fbd)


### Conventions:
* HE: Higher Education
* UG: Undergraduate
* PG: Postgraduate
* Year Notation: e.g., 2017 represents the 2017/18 session.
  
## Definitions:

* Domicile: the student's original place of residence before admission (HESA).
* HE Provider: Includes colleges, universities, and higher education providers (HESA).
* Region of HE Provider: Refers to the region where the domicile is located.

## Key Findings:

* Approximately 13.02 million HE students were admitted from 412 domiciles into 4 regions of HE providers between 2017/18 and 2021/22, showing an 18.7% increase.
* Greater London ranked 1st among domiciles, China 2nd, and India rose from 18th to 3rd position.
* Nigeria jumped from 52nd to 8th place, likely due to high rate of emigration.
* England had the most HE students (10.7 million), while Northern Ireland had the fewest (300,000).
* Among personal characteristics, females constituted 56.9% of HE students, with UK female students exceeding males by 39.4%.
* About 38.8% of HE students were 20 and under, and 42.02% of non-UK domicile students were 21–24 years old.
* Approximately 14.51% had known disabilities.
* Students with no religion comprised 34.56%, followed by Christianity at 23.04%.
* 73.96% were undergraduates (9.63 million), with 16.52% of the 3.39 million PG students engaged in PG research.
