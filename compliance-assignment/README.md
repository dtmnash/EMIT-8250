# NIST / FISMA Compliance Project

## Overview
In this assignment you will pick a company, identify its strategic goals and maturity, and then step through the FISMA/NIST certification process to examine a system for new acquisition. 

As part of this assignment, you will *first pick a company* and then *prepare a document* with the following structure:

1. Strategic company information
2. Company Maturity
3. System information
4. System Assessment and Managerial Certification Recommendations

Each section is discussed in detail below.

### Strategic Company information
#### Task
The purpose of this part of the assignment is to identify important strategic information that guides how the company operates.

#### Report Structure
The `Strategic company information` section should contain the following:

1. `Name` - The company's name
2. `Executive Summary` - Write a one paragraph synopsis of what the company does. When writing your summary answer questions such as, what products and services the business offers, what its customer base is, how maturity is the organization (e.g. is it a startup or an established company?), what risks does it face, how does it make money?
3. `Strategic Business Goals` - In a bulleted list under the summary, identify at a few business goals/objectives associated with the company, (i.e. what are they trying to achieve as a business?). Include a sentence for each that explains the goal. **Please do not** list `make money` or `grow` as business objectives. Be specific. For instance, a goal for `Google` might be `Improve search precision` or `Increase ad product targeting through embedded in-home IoT products`
4. `IT Function` - Below that write a single paragraph about how you imagine IT needs to support the company for it to achieve its stated goals.

### Company Maturity
#### Task
The purpose of this assignment is to identify how mature the company you selected is with respect to its information security and IT processes. Look to its existing company policies (if you can find them), its publically releasable data, and make your best guesses about the company, as you do the following:

Open the attached [ISO/NIST maturity assessment tool](./assessment-tool.xlsm) and identify the company’s maturity levels. The tool has a number of questions you can ask yourself about the company. For each question, assign your answer a value of `Not performing (0)` to `continuously improving (5)` or `Not applicable`. Your selections should fit with the governance objectives and business goals of the company. For instance, if it is a startup you probably shouldn't have 5s across the board in info. Sec. 

#### Report Structure
The `Company Maturity` section of your report should just contain a single sentence that identifies how mature your company is and reports the overall maturity value calculated from the assessment tool spreadsheet. Please also attach the spreadsheet itself to your submission in canvas.

### System Information
#### Task
Assume the company is looking to acquire and use a new system. Pick an off-the-shelf piece of software of your choice for the company to acquire. Identify how the company might use it, the assets that might be involved in its use, and then identify the criticality of the system using the [FIPS 199/200](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.199.pdf).

> Selecting a mature open source product with a large community is wise - because it means there will be more information available about it.

#### Report Structure
The `System Information` section of your report should contain the following:

1. `Name of Product` - The name of the software you examined and a link to where one can find out more about it.
2. `Usefulness` - Identify how your selected company might use this software.
3. `Related Assets` - Identify relevant company assets that this software might interact with (E.g. will it use PII, intellectual property, etc). Be specific - don't list 'information'. Example: company is a retail chain (e.g. target) product is a point-of-sale system like [Shopkeep](https://www.shopkeep.com/). In this case, assets might be customer data such as name, address, credit card data, etc.
4. `Criticality Assessment` - Use FIPS 199/200 to identify a criticality for the system based on the strategic objectives you identified for the company, the use the company might have for the system, and the importance of the related assets. You should list the FIPS-specified tuple for each aspect of criticality.

### System Assessment and Managerial Certification Recommendations
#### Task
Given your previous work and the criticality assessment, select a [NIST SP800-53 security control baseline](https://nvd.nist.gov/800-53/Rev4/impact/high) appropriate for your system using the 800-53 Low/Moderate/High baselines. Once selected, review some of the controls from the baseline. Write a short essay addressing the following questions:

- How might an information security team assess these controls?  
- What management strategies could be employed to effectively ensure the security team rigorously evaluates the system for compliance? 
- What is demonstrable evidence of compliance?  

#### Report Structure
The `System Assessment and Managerial Certification Recommendations` section of your report should contain the short essay addressing the questions above.

## Submission
Prepare a report, of type .md, .pdf, .doc, or .docx, that contains the listed sections above in the format specified. Submit your report to Canvas.
