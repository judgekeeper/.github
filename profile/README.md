<p align="center">
  <a href="https://github.com/judgekeeper/judgekeeper">
    <img src="banner.png" alt="judgekeeper: Check your LLM-as-a-judge in 5 steps. Find. Mark. Measure. Fix. Re-check." width="820">
  </a>
</p>

## Check your LLM-as-a-judge in 5 steps.

Find. Mark. Measure. Fix. Re-check.

An LLM-as-a-judge is an AI model that grades the answers of another AI model. **judgekeeper** shows how often your LLM-as-a-judge agrees with your own Pass or Fail marks (TPR and TNR, each with its range), and helps you write a better rule. It is open source (Apache-2.0) and runs on your own computer.

In your project folder, in its virtual environment:
```
pip install judgekeeper
judgekeeper
```
Or, with no virtual environment: `uvx judgekeeper`.

Works with promptfoo, DeepEval, Inspect AI, MLflow or your own file (such as a CSV, TSV or JSONL file).

- **Code:** [judgekeeper/judgekeeper](https://github.com/judgekeeper/judgekeeper)
- **Website:** [www.judgekeeper.com](https://www.judgekeeper.com)
- **Package:** [pypi.org/project/judgekeeper](https://pypi.org/project/judgekeeper/)
