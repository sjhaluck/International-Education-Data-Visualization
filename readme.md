# PISA 2012: Parental Influence on Academic Performance
## by Scott Haluck


## Dataset
The Programme for International Student Assessment (PISA) 2012 study gathered data about student performance, student life, and school quality from 65 countries. The data is expansive in both breadth and depth, so it can be analyzed from a variety of perspectives.

[PISA Source Data](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip&sa=D&ust=1554482573645000)
[PISA Technical Manual](https://www.oecd.org/pisa/pisaproducts/PISA%202012%20Technical%20Report_Chapter%2016.pdf)

The variety of data collected addresses numerous aspects of student life, behavior, culture, history, family, and school characteristics. Due to the significant amount of data available, not all variables could be analyzed. To help focus the analysis, the following characteristics were chosen (column name, followed by description):
* student_id: student identification number
* gender: student gender
* oecd: country OECD partnership status
* country: country name
* preschool: student preschool experience
* age_edu_start: age at which student began education
* immigration: student immigration classification
* culture_dist: a measure of distance between student culture of origin and current culture
* age_lang_start: age range at which student began learning the test language
* parent_edu: highest level of parental education in the home
* father_edu: highest level of education (father)
* mother_edu: highest level of education (mother)
* parent_occ: highest level of parental employment in the home
* father_occ_status: level of employment (father)
* mother_occ_status: level of employment (mother)
* status_index: family economic, social, cultural status index
* fam_struct: family structure (number of parents in the home)
* home_edu_res: index of access to home educational resources
* math_score: student math performance
* read_score: student reading performance
* science_score: student science performance
* math_anxiety: index of student math anxiety
* math_behaviors: index of student engagement in math behaviors
* math_efficacy: index of student confidence in math ability
* math_work_ethic: index of student work ethic in math
* math_norm: index of student social exposure to math
* belong: index of student sense of belonging at school
* lang_min: weekly instructional minutes in reading and language arts
* math_min: weekly instructional minutes in math
* science_min: weekly instructional minutes in science
* teacher_math_sup: index of teacher support of math
* teacher_form: index of teacher use of formative assessment


## Summary of Findings

### Univariate Analysis Findings
* Preschool enrollment, language initiation, and family structure provide good sorting values to investigation early family decisions on the performance, behaviors, and attitudes of the student.
* There are extreme values in some of the student behaviors, teacher behaviors, and social, economic, and cultural index of the families.

### Bivariate Analysis Findings
* Preschool is related to higher academic performance
* Age of language learning is related to academic performance
* Parental occupation status is related to student academic performance
* Parental education attainment is related to academic performance, access to home educational resources, parental occupation level, and family status index
* Family status index is related to access to home educational resources
* Family status index is related to academic performance and student self-efficacy
* Family parental structure is related to status index and academic performance
* Gender is related to language score (but not math or science) and levels of math anxiety
* Math self-efficacy is related to math performance
* Math social environment is related to engagement in math behaviors
* Country's OECD classification is related to status index and student performance
* Student performance by country and average status index by country has a few exceptions that may be worth investigating

### Multivariate Analysis Findings
* Preschool experience is related to an academic advantage, regardless of when the student began learning the test language
* At any education level, parents improve the social status of the family as they improve their job prospects
* When controlling for parental education level, family social status is a positive predictor of student academic performance
* Having a parent in the home protects the relationship between family social status and academic performance
* The academic advantage for OECD countries increases slightly over non-OECD countries as the family gains more social status in those countries
* Despite the strong relationship between family social status and student academic performance, there are countries that perform above their average social status to achieve higher academic scores and there are countries that perform below their average social status and achieve lower academic scores. These discrepancies are consistent across parental education level and family social status in these respective groups.
* When comparing countries on the two extremes of performance as described above, there is a significant difference in the relationship between academic instructional minutes (in math) and student academic performance. The group of highest performing countries have a strong positive relationship between instruction minutes and academic performance, while the group of lowest performing countries have a nearly zero relationship.

## Key Insights for Presentation
Finding: Parents are the key to a student's academic success.

* The parent's effect starts early, before the child is born: Parental education has a  positive relationship with student academic success. Parents: Maximize your education to enhance your children's.
* It continues into the professional world: Parental occupation is linked to gains in family social status, which is linked to higher academic performance.
* Once the child arrives, start early: Preschool is a great investment in your child's future, regardless of future immigration that may bring new cultures and languages.
* Hold on till the end: Students with a parent in the home enjoy a stronger relationship between family social status and academic benefit.
* Looking to have an extreme impact? It may require a move: The quality of academic performance in some countries is considerably lower than social status would predict. This required calculating an additional variable, performance index, comparing how a country's average academic performance percentile compares to its average social status percentile.
