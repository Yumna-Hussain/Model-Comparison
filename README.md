# Model-Comparison
Comparing different AI models

## Objective

This project compares multiple Large Language Models (LLMs) on a document summarization task using the same input document and prompt.

## Models Tested

- ChatGPT
- Claude
- Gemini
- DeepSeek

## Input Document

`FYP UPDATED SCOPE.pdf`

## Prompt

```
Summarize the following document in 200 words maximum.
Focus on the main ideas, important findings, and conclusions.
Do not include information that is not present in the document.
Organize the summary into clear paragraphs.
```

## Evaluation Criteria

- Summary Quality
- Accuracy
- Conciseness
- Hallucinations

## Comparison Table

| Model | Summary Quality | Accuracy | Conciseness | Hallucinations | Overall |
| :--- | :---: | :---: | :---: | :--- | :---: |
| **Claude** | 9.8 | 9.9 | 9.3 | None detected | **9.8/10** |
| **Gemini** | 9.6 | 9.7 | 9.8 | Minor wording inference | **9.6/10** |
| **ChatGPT** | 9.5 | 9.8 | 9.2 | None detected | **9.5/10** |
| **DeepSeek** | 8.7 | 9.3 | 9.5 | Minor inference | **9.1/10** |

## Final Observations

- **Claude** produced the most well-structured and comprehensive summary. It captured nearly all key points from the source document without introducing unsupported information. It also mentioned information present in charts and gave contextual information about the document.
- **Gemini** generated the concise summary and effectively highlighted the main ideas. It provided context about document. Provided most easy to understand summary.
- **ChatGPT** delivered a balanced summary with high factual accuracy and good readability. It remained faithful to the source material without any noticeable hallucinations. It did not covered much contextual information about document 
- **DeepSeek** produced a clear and concise summary but occasionally made minor inferences, making it slightly less reliable than the other models for factual summarization.

## Recommendations

- **Claude** is recommended for tasks requiring high-quality, detailed, and accurate document summaries.
- **Gemini** is best suited for scenarios where concise summaries are preferred while still retaining the essential information.
- **ChatGPT** is a strong choice for general-purpose summarization, offering a good balance between readability, accuracy, and completeness.
- **DeepSeek** can be used for quick summarization tasks, but its outputs should be reviewed to ensure that inferred information has not been introduced.

## Conclusion

Based on this comparison, **Claude** performed best overall due to its superior summary quality, excellent accuracy, and absence of hallucinations. **Gemini** ranked second by producing highly concise summaries with only minor wording inferences. **ChatGPT** demonstrated strong factual accuracy and readability, making it a reliable general-purpose summarization model. **DeepSeek** performed well but introduced slight inferences, placing it behind the other evaluated models for this task.
