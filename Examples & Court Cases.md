```table-of-contents
```

# Big Data Disparate Impact

## How Data Mining Discriminates

### Defining the "Target Variable" and "Class Labels"

- Examples of model prediction
	- Spam, Fraud detection, Credit scoring, and insurance pricing
- Defining target variable for credit scoring
	- Unlike fraud or spam, “creditworthiness” is an artifact of the problem definition itself.
	- Creditworthiness is a social construct, not a direct measure of ability to repay debt. (Refer p.g. 9)
- Defining target variable for good employee
	- “Good” must be defined in ways that correspond to measurable outcomes: relatively higher sales, shorter production time, or longer tenure.
	- Go beyond categories: predict sales figures, production speed, or tenure length for ranking.
	- Holistic approach? Use annual review grades (assuming they reflect overall performance). But annual review grades (used as target variable) inherit inconsistency issues from subjective human evaluations.

### Training Data

#### Labeling Examples

- Fraud & spam data mining
	- Customers label transactions (fraudulent charges) & emails (spam) for providers.
- St. George's Hospital's 
	- Admissions historically disfavored minorities and women. They used an algorithm trained on those decisions to sort future applicants. In drawing rules from biased prior decisions, St. George’s Hospital unknowingly devised an automated process that possessed these very same prejudices. The algorithm perpetuated the bias, unknowingly favoring white and male applicants.
- Sweeney's Study on Google Ads
	- Google Ads showed arrest records more for Black-sounding names than White-sounding names. 
	- Google's algorithm prioritizes ads likely to get clicks based on past user behavior.
	- This could reflect existing racial biases in user clicks, perpetuating them.
- LinkedIn's Talent Match
	- Recommends candidates based on employer interest.
	- If employers show bias (e.g., against protected classes), Talent Match could perpetuate it by recommending similar candidates.

#### Data Collection

- Street Bump App: 
	- Uses smartphones to detect potholes.
	- Unequal smartphone ownership across income levels.
	- Underreporting of potholes in poorer (minority) communities.
	- City resource allocation based on biased data could further disadvantage these communities.

#### Feature Selection

- Redlining: 
	- Using broad criteria (e.g., neighborhood) for financial decisions (loans etc.).
	    - Doesn't capture variations within groups leading to unfair outcomes for some individuals.
	    - Historically based on racial bias, but now justified by cost-efficiency (cheap, easy data).
	    - Often disadvantages protected classes due to their geographic concentration.
	- Redlining is illegal: Unfair to discount entire areas based on demographics.

#### Proxies

- Focusing on predicted employee competence can disadvantage protected groups if the criteria used are less common among them.

## Title VII Liability for Discriminatory Data Mining

### Disparate Impact

- Griggs v. Duke Power Co.
	- Established the "business necessity" defense in disparate impact cases.
	- Unclear distinction between job-relatedness):
		- Must be related to job performance.
	    - Measurably predict success in the job.
	    - Not simply assess personal characteristics unrelated to the work.
	- Key Point: Focuses on future job performance, not past qualifications.
		- They can't be based on things like education (high school diploma) that aren't proven necessary for the job itself. (e.g., Black employees in similar jobs performed well without a diploma)
		- The employer couldn't show the new requirements were necessary for the job or that they studied their impact beforehand.
		- Vague justifications like "better workers" aren't enough under the business necessity defense.
	- More details [Optional]
		- **Griggs v. Duke Power Co.:** Black employees denied promotions due to high school diploma or test requirements.
		- **Disparate Impact:** Requirements disadvantaged Black employees (less likely to have qualifications).
		- **Failed Defense:** Company couldn't prove requirements were necessary for the jobs (not related to performance).
		- **Impact:** Established business necessity defense for employers in disparate impact cases (policies need a job-related justification).
- Transition of Business Necessity Definition
	- Pre-1979
		- Stricter standard - Practice had to be "essential" for the job.
	- 1979 
		- NYC Transit Authority v. Beazer: Looser standard - Upheld a rule barring drug users (including recovering addicts) with minimal justification.
	- 1989 
		- Wards Cove Packing Co. v. Atonio: Even looser standard - Shifted burden to plaintiffs to prove lack of business necessity, called it "business justification."
	- 1991 Civil Rights Act
		- Overruled Wards Cove, reset standards to pre-1989 strictness.
	- Post-1991
		- Confusion persists due to previous looser interpretations.
- Albemarle Paper Co. v. Moody
	- “If an employer does then meet the burden of proving that its tests are ‘job related,’ it remains open to the complaining party to show that other tests or selection devices, without a similarly undesirable racial effect, would also serve the employer’s legitimate interest in ‘efficient and trustworthy workmanship.’”
	- This burden-shifting scheme was codified in the 1991 Act as the “alternative employment practice” requirement.

# Autonomous Weapon Systems

- South Korean SGR-A1
	- The South Korean SGR-A1 is a stationary, armed robot that allegedly has a fully autonomous setting, but South Korea maintains that it is used only in conjunction with a human operator and exclusively to monitor the relatively static Korean demilitarized zone.
- 