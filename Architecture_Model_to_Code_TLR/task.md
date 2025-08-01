Title: Architecture Model to Code Traceability Link Recovery (TLR)

Title (Short for Leaderboard): Model to Code TLR

Description: This task involves the extraction of trace links between architecture component models and source code. The goal is to identify and establish connections between elements in architecture models and their corresponding implementations in the codebase. The granularity of the task is at the model element level (i.e., components and interfaces), where each architecture model element is linked to specific code artifacts (i.e., classes or directories (packages)).

Description (Short for Leaderboard): Evaluation of automated traceability link recovery (TLR) approaches for architecture model elements to code artifacts TLR.

Input Format:
* Architecture Component Model: A UML (Papyrus UML) or PCM (Palladio Component Model) file representing the architecture components, interfaces, and their relationships.
* Source Code:
    a) The link to the source code files of the system with specific commit hash.
    b) A JSON (ACM) file containing the relevant elements from the code. Extracted with [CodeModelExtractorCLI](https://github.com/ArDoCo/CodeModelExtractorCLI).

Output Format: A CSV file representing the trace links between model elements and code artifacts with the following columns:
- `ae_id`: The unique identifier of the architecture element.
- `ce_id`: The path of the corresponding code element.

Example: A snippet from the dataset capturing the relevant format knowledge. (Can be provided in a single markdown with input and output format)

Dataset URL: https://github.com/ardoco/benchmark and https://doi.org/10.5281/zenodo.6966831

Metrics:
- Precision: The ratio of correctly identified trace links to the total number of identified trace links.
- Recall: The ratio of correctly identified trace links to the total number of actual trace links.
- F1 Score: The harmonic mean of precision and recall.
