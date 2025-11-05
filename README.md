Use Case#: 18

Title name:

Insurance Agency Files mapping for Insurance Carrier

Problem Statement:

Agencies send consolidated summaries of insurance policies as a single report to Insurance Carriers. However, the mapping to target (Insurer end) is manually intensive task due to variations in the file headers.

Steps:

Create a master file (csv or json) representing the insurer data format

Create a sample policy or claim feed file with Headers (similar to the agency feed for csv or json) for 2-3 agencies.

Use LLM to map the agency and insurer policy feeds

Ensure the following are handled: Field names variations, Missing Fields, Data Format conversions, Additional Fields, Duplicate Fields handling, Use the content to arrive at target for missing column names

Data Requirements:

Agency File data, Insurer Policy Data Format

Expected Output:

Mapping of agency files to insurer format highlighting the differences along with justification for mapping other than directly mapped data.