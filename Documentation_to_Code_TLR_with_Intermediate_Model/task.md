Title: Documentation to Code Traceability Link Recovery (TLR) with Intermediate Model (Architecture Component Model)

Title (Short for Leaderboard): Documentation to Code TLR (with Intermediate Model)

Description: This task involves the extraction of trace links between architecture documentation and source code, using the architecture component model as an intermediate step. The goal is to identify and establish connections between textual descriptions in architecture documentation and their corresponding implementations in the codebase. The granularity of the task is at the sentence level, where each sentence in the documentation is linked to specific code artifacts (i.e., classes or directories (packages)).

Description (Short for Leaderboard): Evaluation of automated traceability link recovery (TLR) approaches for documentation sentences to code artifacts TLR with architecture component models.

Input Format:
* Architecture Documentation: A text file containing the sentences of the architecture documentation. Each line contains a sentence.
* Architecture Component Model: A UML (Papyrus UML) or PCM (Palladio Component Model) file representing the architecture components, interfaces, and their relationships.
* Source Code:
    a) The link to the source code files of the system with specific commit hash.
    b) A JSON (ACM) file containing the relevant elements from the code. Extracted with [CodeModelExtractorCLI](https://github.com/ArDoCo/CodeModelExtractorCLI).

Output Format: A CSV file representing the trace links with the following columns:
- `sentenceID`: The number of the sentence in the architecture documentation (starting at 1).
- `codeID`: The path of the corresponding code element.

Example: A snippet from the dataset capturing the relevant format knowledge. (Can be provided in a single markdown with input and output format)

Dataset URL: https://github.com/ArDoCo/Benchmark and https://doi.org/10.5281/zenodo.6966831

Metrics:
- Precision: The ratio of correctly identified trace links to the total number of identified trace links.
- Recall: The ratio of correctly identified trace links to the total number of actual trace links.
- F1 Score: The harmonic mean of precision and recall.
