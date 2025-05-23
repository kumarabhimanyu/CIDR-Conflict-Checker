
# CIDR Conflict Checker for On-Prem & Cloud IP Ranges

## Description
A PowerShell script that detects overlapping IP ranges between CIDR blocks from a CSV input. It validates input structure, logs errors, and ensures robust IP conflict detection—ideal for cloud migration planning.

## Business Problem
In hybrid and multi-cloud environments, overlapping IP ranges between on-premises and cloud networks can lead to routing conflicts, service disruptions, and security vulnerabilities. Manual validation is error-prone and inefficient, especially at scale.

## Business Value
This script automates the detection of IP conflicts between CIDR ranges, ensuring clean network segmentation across environments. It improves migration readiness, reduces risk of outages, and saves time by validating input structure and logging errors for traceability.

## Usage Instructions

1. **Place the Script and CSV File**: Ensure the PowerShell script and the input CSV file are in the same directory. The CSV file should have two columns: `CIDR1` and `CIDR2`.

2. **Run the Script**: Execute the PowerShell script. You will be prompted to enter the path to your input CSV file.

3. **Output Files**: The script will generate two output files:
    - `output.csv`: Contains the results of the CIDR conflict check.
    - `error_log.csv`: Contains any errors encountered during processing.

4. **Review Results**: Check the `output.csv` for conflicts and `error_log.csv` for any errors that occurred during execution.

