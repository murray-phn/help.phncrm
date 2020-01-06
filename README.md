# phn-crm-docs

https://phn-crm.readthedocs.io/en/latest/ 
 
This help centre is designed for PHN staff who have already bought the PHN CRM SAAS. It is not intended as a 'sales pitch'.

## Setup

1. Install Python 3.7 - https://www.python.org/downloads/release/python-376/

1. Make sure PATH includes the paths to Python 37

1. Open PowerShell in the root repo folder

1. Run 'pip install mkdocs'

1. Run 'pip install mkdocs-material'

1. Run 'mkdocs build'

1. Run 'mkdocs serve'

1. Open 'http://127.0.0.1:8000'

If pip is not found, add the path to it's executable to the PATH variable.

## How to edit

1. Create/update your MD files
2. Update the mkdocs.yml file (this is what defines the side menu)
3. Run 'mkdocs build' and push your changes to the repo
4. The live site will update after push

You can use 'mkdocs serve' to see live-edits in your local environment before pushing changes.