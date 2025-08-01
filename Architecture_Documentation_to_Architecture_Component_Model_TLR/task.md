Title: Architecture Documentation to Architecture Component Model Traceability Link Recovery (TLR)

Title (Short for Leaderboard): Documentation to Component Model TLR

Description: This task involves the extraction of trace links between architecture documentation and architecture component models. The goal is to identify and establish connections between textual descriptions in architecture documentation and corresponding components in architecture models.
The granularity of the task is at the sentence level, where each sentence in the architecture documentation is linked to a specific architecture component or interface in the model.

Description (Short for Leaderboard): Evaluation of automated traceability link recovery (TLR) approaches for architecture documentation sentences to architecture components TLR.

Input Format:
* Architecture Documentation: A text file containing the sentences of the architecture documentation. Each line contains a sentence.
* Architecture Component Model: A UML (Papyrus UML) or PCM (Palladio Component Model) file representing the architecture components, interfaces, and their relationships.
Output Format: A CSV file representing the trace links between components and sentences with the following columns:
- `modelElementID`: The unique identifier of the architecture component.
- `sentence`: The number of the sentence in the architecture documentation (starting at 1).

Example : A snippet from the dataset capturing the relevant format knowledge. (Can be provided in a single markdown with input and output format)

Dataset URL: https://github.com/ardoco/benchmark and https://doi.org/10.5281/zenodo.6966831

Metrics:
- Precision: The ratio of correctly identified trace links to the total number of identified trace links.
- Recall: The ratio of correctly identified trace links to the total number of actual trace links.
- F1 Score: The harmonic mean of precision and recall.

