<p align="center">
  <a href="https://github.com/judgekeeper/judgekeeper">
    <img src="banner.png" alt="judgekeeper: The keeper of human judgment for AI. Read. Measure. Fix. Re-check." width="820">
  </a>
</p>

<p align="center">
  <a href="https://www.judgekeeper.com"><b>Website</b></a> ·
  <a href="https://www.judgekeeper.com/start.html"><b>Guide</b></a> ·
  <a href="https://github.com/judgekeeper/judgekeeper"><b>Code</b></a> ·
  <a href="https://pypi.org/project/judgekeeper/"><b>PyPI</b></a>
</p>

Human judgment decides what's right. **judgekeeper** shows how often each automated check agrees with it, from an LLM-as-a-judge grading one answer to a reviewer checking each step of an agent, and whether agreement goes up or down after each change. It is open source (Apache-2.0) and runs locally.

<p align="center">
  <img src="https://raw.githubusercontent.com/judgekeeper/judgekeeper/main/docs/assets/demo.webp" alt="judgekeeper finds the results, opens the marking page, and shows how often the LLM-as-a-judge agrees with you." width="760">
</p>

### The 4 steps

1. **Read.** Read your eval results and your labels, such as a Label Studio export, or mark answers Pass or Fail in your browser.
2. **Measure.** See how often your check agrees with you, and how much your people agree with each other.
3. **Fix.** Write a better rule and test it on marks kept aside.
4. **Re-check.** Change your check's prompt or model and see if agreement goes up or down.

### Install

In your project folder, in its virtual environment:
```
pip install judgekeeper
judgekeeper
```
Or, with no virtual environment: `uvx judgekeeper`.

Works with promptfoo, DeepEval, Inspect AI, MLflow, Label Studio exports or your own CSV, TSV or JSONL file. For agents, `judgekeeper steps` checks a reviewer's first wrong step.
