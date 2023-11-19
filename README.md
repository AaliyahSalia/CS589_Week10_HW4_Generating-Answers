# CS589_Week10_HW4_Generating-Answers

*Google slides:*

**Generating Answers**

*Step 1: Preprocessing input texts*
Step 1.1: Split into a list of paragraphs
Step 1.2: Clean up to remove empty spaces and new line

*Step 2: Embeddings*
Step 2.1: Chunking: Get the embeddings (vectors) from input texts
Step 2.2: Build a search index from embeddings (vectors) 
Step 2.2.1: Check the dimensions of the embeddings
Step 2.2.2: Create the search index, pass the size of embeddings (size of vector) 
Step 2.3: Add all the vectors to the search index

*Step 3: Searching Articles*

*Step 4: Generating Answers*
Step 4.1: Generating Answers - Test Case 1
Step 4.2: Generating Answers - Test Case 2 
Step 4.3: Generating Answers - Test Case 3


**Input Texts**
Textual data or documents that you want to process and make searchable.

**Embeddings**
Numerical representations of input texts obtained through techniques like word embeddings or pre-trained models.

**Vectors**
Numerical representations of input texts in a vector space. These vectors are derived from embeddings.

**Search Index**
A data structure used to organize and efficiently retrieve vectors (embeddings) of input texts.

**Process**
The overall process of working with input texts, embeddings, vectors, and search index involves the following steps:
*Step 1: Generate Embeddings from Input Texts*
In this step, you convert input texts into numerical embeddings using pre-trained models or embedding techniques.

*Step 2: Create Vectors from Embeddings*
After obtaining embeddings for input texts, you generate vectors that represent these embeddings in a vector space.

*Step 3: Create Search Index from Vectors*
In this step, the vectors derived from embeddings are used to create a search index.
The search index organizes and stores these vectors for efficient retrieval.
