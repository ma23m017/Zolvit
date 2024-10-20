# Zolvit

## How to Run

### Step 1: Set Up the Environment

Clone this repository or download the notebook file to your local machine.
Ensure all dependencies are installed using the above installation command.

### Step 2: Load the Data

The code expects an input CSV file or structured tabular data containing the following fields:

- taxable_value
- sgst_amount
- cgst_amount
- igst_amount
- sgst_rate
- cgst_rate
- igst_rate
- tax_amount
- tax_rate
- final_amount
- invoice_number
- invoice_date
- place_of_supply
- place_of_origin
- gstin_supplier
- gstin_recipient
  
### Step 3: Run the Code

Open the Jupyter Notebook (zolvit-assignment.ipynb) using the command below:

### "jupyter notebook zolvit-assignment.ipynb"

Execute the notebook cells step by step by pressing Shift + Enter to load, process, and validate the invoice data.

### Step 4: Validation

The notebook contains validation logic using regular expressions for fields such as account_number and ifsc_code.
The system checks for format correctness in these fields and ensures that all extracted data meets the predefined rules.

### Step 5: Output

The code outputs the validated data and highlights any discrepancies found during processing.
You can modify the regex checks or the extraction logic as needed to fit different data formats.
