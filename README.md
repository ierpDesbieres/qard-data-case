# Qard data test case

1. Context

You are given a large quantity of PDFs files, those files contain administrative informations about some french companies. We want to extract and structure some information out of those PDFs, with the following steps we want you to implement a solution to do so.

2. Steps

- For exploration sake, you are given a subset (~10) of our dataset (~10^6). The files are in `/data`. **Take a look at the files**.
- As the production dataset is very large we want to have and efficient way of handeling the processes. Install Spark on your machine (Standalone) following this guide [Spark Doc](https://spark.apache.org/docs/latest/index.html) 
- Now that we have installed Spark we want to submit a `pyspark` job to our local "cluster" in order to do OCR on our sample PDFs. **Build a pyspark script that handle OCR** of our files (You can take a look at `tesseract-ocr` and `pytesseract`)
- Propose a way to **extract and format people names** out of the ocr results.

3. Restitution
- The case should be solved using Python
- We expect you to send us the results as a git repository
- Don't hesitate to comment or add anything that you judge relevant to the case.
