Transaction Cleaner

A Python script to clean, normalize, and summarize Excel transaction files.

Features

Load raw transaction Excel files.

Normalize string and date columns.

Remove unnecessary columns (Conversion Amount, Foreign Currency Amount).

Exclude November transactions.

Automatically detect and remove reversal transactions (e.g., payment reversals, failed payments).

Aggregate transactions by Code and other relevant fields.

Label each transaction as Credit or Debit.

Export cleaned and summarized data to a new Excel file.

Requirements

Python 3.8+

Libraries: pandas, numpy, openpyxl

Install dependencies:

pip install pandas numpy openpyxl

Usage

Place raw Excel files in the project folder.

Update files_to_process list in the script with filenames to clean.

Run the script:

python transac_clean_demo.py


Cleaned files will be saved in the cleaned_transac folder.

Output

A cleaned Excel file per input, with:

Reversals removed.

Dates and strings normalized.

Transactions grouped and summarized.

Particulars column indicating Credit or Debit.
