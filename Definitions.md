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

# Mozilla v FCC

## Petitioners Brief

- **1980 Computer II Order:** FCC declared that Title II of the Act applied to carriers’ provision of “basic” service, defined as “a pure transmission capability” that included “analog or digital transmission of voice, data, video, etc., information.” 
- **Telecommunications Act of 1996:** The Telecommunications Act of 1996 declared “a telecommunications carrier shall be treated as a common carrier . . . to the extent it is engaged in providing telecommunications services . . . .”
- **Telecommunications Carrier:** provider of telecommunications services, which is “an offering of telecommunications for a fee directly to the public. . . .”
	- **Telecommunications:** The transmission, between or among points specified by the user, of information of the user’s choosing, without change in the form or content of the information as sent and received.
- **Information Services:** Offering of a capability for generating, acquiring, storing, transforming, processing, retrieving, utilizing, or making available information via telecommunications . . . .

# Autonomous Weapon Systems

- Roughly categorized as: 
	- **Inert:** objects requiring contemporaneous operation by a human being to be lethal
	- **Automated:** Automated weapon systems may be deployed long before they engage an unknown and unpredicted target, but they act in a predictable manner. 
		- A dumb landmine or tripwire sentry gun acts independently, but it does not “select” a target; rather, it responds predictably to a preset trigger
	- **Semi-autonomous:** has autonomous capabilities in functions relevant to target selection and engagement—but it cannot both select and engage targets independently.
		- Most “fire and forget” missiles and unmanned drones in operation today are semi- autonomous, as a human operator must take some affirmative action for a target to be selected or for a selected target to be engaged.
	- **Autonomous:** an autonomous weapon system is capable of independently selecting and engaging targets based on conclusions derived from gathered information and preprogramed constraints.

# Free Speech is a Triangle

- **Old School Speech Regulation:** Nation-states use threats of fines, penalties, imprisonment, or other forms of punishment or retribution to regulate or control the speech of individuals, associations, and media companies.
- **New School Speech Regulation:** Nation-states and supranational entities regulate speech by pressuring or co-opting private internet-infrastructure companies to surveil, police, and control speech on their behalf, rather than directly regulating speakers themselves​
- **Collateral Censorship:** Collateral censorship occurs when the state targets one entity (A) to control the speech of another entity (B), effectively using A to regulate speech on the state’s behalf, often leading to overblocking or overfiltering of content by A to avoid penalties.
	- Example: Newspaper being liable for what their reporters write and their advertisers advertise.
- **Digital Prior Restraint:** involves imposing liability on internet-infrastructure providers unless they surveil, block, or remove speech that others complain about, mimicking classic prior restraint by preventing speech without judicial determination and lacking transparency or due process​
- **Private Governance:** refers to the practice of privately owned internet-infrastructure companies, such as social media platforms, governing online speech and behavior through the enforcement of their own policies, rules, and algorithms, effectively taking on roles traditionally associated with state governance
- **Privatized Bureaucracy:** phenomenon where private digital infrastructure companies, like social media platforms, perform regulatory functions traditionally associated with the state, including content moderation and speech regulation, in response to legal pressures or government demands
- 