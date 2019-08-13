# CIS-Generator
Create a CIS workbook (https://www.fedramp.gov/templates/) from an SSP and optionally supporting documentation (like an addendum with SRG security/privacy controls)

## Requirements
Assuming python and pip are already set up:
Run `pip install -r requirements.txt` to install the dependencies (openpyxl and python-ssp)

## Usage
Required arguments are the following:
`.\cis_generator.py --out my-cis.xlsx --template mod-template.xlsx --ssp my-security-plan.docx`

If the SSP is split into two documents (like an addendum), you can optionally add `--addendum` and point to the relevant docx file.