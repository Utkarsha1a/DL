# What is a Resume Scanner?
Most businesses’ human resources departments today use software known as an Applicant Tracking System which is used to select the right candidates for a particular job. Such software scans a document to extract and match the keywords on a resume with the skills and qualifications needed to perform a particular job. This is nothing more than resume scanning and an application used to perform this task is known as a resume scanner.

Almost all large companies use resume scanning software to get the best candidates for the job posted in a matter of time. In the repository, I’ll walk you through how to create a resume scanner using the Python programming language.

#### Approach:
I want to create a Python program that will return the percentage % match between a resume and a job description.

PythonPackage => **Docx2txt**

First, we will import libraries and then will upload our resume and job Description files.
After that we are using CountVectorizer process to Extracting Features from Text.
CountVectorizer convert a collection of text documents to a matrix of token counts.
Then we used Cosine Similarity that is Text Similarity Metric which is used to determine how the two text documents close to each other in terms of their context or meaning.

Mathematically, Cosine similarity metric measures the cosine of the angle between two n-dimensional vectors projected in a multi-dimensional space. The Cosine similarity of two documents will range from 0 to 1. If the Cosine similarity score is 1, it means two vectors have the same orientation. The value closer to 0 indicates that the two documents have less similarity.
