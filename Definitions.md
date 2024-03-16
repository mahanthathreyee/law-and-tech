```table-of-contents
```

# Big Data Disparate Impact

## How Data Mining Discriminates

### Defining the "Target Variable" and "Class Labels"

- **Target Variable**: Defines what data miners are looking for.
- **Class Variables**: Divide all possible values of the target variable into mutually exclusive categories.

### Training Data 

- **Training Data:** The data that functions as examples for the model to learn from.

#### Labeling Examples

- **Labeling Examples:** Labeling examples is the process by which the training data is manually assigned class labels.

#### Feature Selection

- **Feature Selection:** Organizations choose which data points to include in analysis (data miners do this too).
- **Redlining:** Using broad criteria (e.g., neighborhood) for financial decisions (loans etc.).
- **Rational Racism:** Special case of bias based on cost-benefit analysis, not prejudice.

#### Proxies

- **Proxies:** Indirect variables used to represent characteristics that can be sensitive or difficult to measure directly. These stand-in variables often correlate with the sensitive characteristic, but they are not the same thing.
- **Redundant Encodings:** Refers to a situation where information about a person's membership in a protected class (like race, gender, etc.) is indirectly revealed by another piece of data.

#### Masking

- **Masking:** Refers to the act of hiding the true intent behind discriminatory practices. Data miners with malicious intent can utilize various techniques to disguise their discriminatory goals and make their actions appear objective or data-driven.

## Title VII Liability for Discriminatory Data Mining

### Disparate Treatment

- **Disparate Treatment:** Unequal treatment of similarly situated people based on a protected class (race, gender, etc.).
	- **Formal Discrimination:** Membership in a protected class is used as an input to the model. It covers both the straightforward denial of opportunities based on protected class membership and the use of rational racism.
	- **Discriminatory Intent:** Requires evidence that the different treatment was motivated by the employee's membership in a protected class, such as race, gender, age, disability, religion, or national origin.
- **McDonnell Douglas framework:** A legal framework used to assess claims of employment discrimination. It outlines the burden of proof for both the employee (plaintiff) and employer (defendant) in such cases.
- **Mixed-motive framework:** a plaintiff need not demonstrate that the employer’s nondiscriminatory rationale was pre-textual, but merely that discrimination was a “motivating factor” in the adverse employment action. As a practical matter, this means that the plaintiff must show that the same action would not have been taken absent the discriminatory motive.

## Disparate Impact

- **Disparate Impact:** Unintentional discrimination that occurs when a facially neutral policy or practice disadvantages a protected class (e.g., race, gender, age) to a greater extent than another group.
- **EEOC Four-Fifths Rule:** If a selection rate for a protected class is less than 80% of the highest selection rate, it suggests potential bias.
- 