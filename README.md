# PthonProject
## Brief:

1. The requirement needs to be developed in Python 3
2. Code should follow pep8 standards and should include pydoc, logging & unit tests
3. Please provide github link for review.

## Requirement:

1. Download the xml from this ## 🔗 (https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://katherineoelsner.com/](https://registers.esma.europa.eu/solr/esma_registers_firds_files/select?q=*&fq=publication_date:%5B2021-01-17T00:00:00Z+TO+2021-01-19T23:59:59Z%5D&wt=xml&indent=true&start=0&rows=100))
2. From the xml, please parse through to the first download link whose file_type is DLTINS and download the zip
3. Extract the xml from the zip.
4. Convert the contents of the xml into a CSV with the following header:
- FinInstrmGnlAttrbts.Id
- FinInstrmGnlAttrbts.FullNm
- FinInstrmGnlAttrbts.ClssfctnTp
- FinInstrmGnlAttrbts.CmmdtyDerivInd
- FinInstrmGnlAttrbts.NtnlCcy
- Issr

5. Store the csv from step 4) in an AWS S3 bucket
6. The above function should be run as an AWS Lambda (Optional)
## Assessment criteria:

1. Percentage of requirements satisfied
2. How clean the code is - in particular simplicity, adhering to python code style conventions and error handling.
3. Follows PEP 8 guidelines
4. We expect pydoc for each class and function with optional type hints(nice to have)
5. Follows standard logging (no print statements). Logs are essential part of troubleshooting application.
6. Unit tests with good code coverage
