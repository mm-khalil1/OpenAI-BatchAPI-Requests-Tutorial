# Batch Prompts with OpenAI BatchAPI Service

<p align="center">
  <img src="https://openai.com/favicon.ico" alt="OpenAI Logo">
</p>

[This notebook](https://github.com/mm-khalil1/OpenAI-BatchAPI-Requests-Tutorial/blob/main/OpenAI%20BatchAPI%20Requests%20Tutorial.ipynb) demonstrates how to efficiently process multiple prompts at once using OpenAI's Batch API. Batch responses may take up to 24 hours.

## Summary

- **Step 1: Prepare JSONL File**  
  Prepare prompts in a CSV file with corresponding IDs. Then convert the CSV to JSONL format.
- **Step 2: Upload JSONL File(s)**  
  Upload the JSONL file(s) to OpenAI's Storage.
- **Step 3: Create a Batch**  
  Create a batch request using the uploaded JSONL file(s).
- **Step 4: Monitor and Retrieve Batch Information**  
  Monitor the batch request status and retrieve information.
- **Step 5: Retrieve Output File Content**

---

Explore the notebook for detailed instructions and code snippets to leverage OpenAI's Batch API for efficient processing of prompts.
