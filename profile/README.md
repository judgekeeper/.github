<p align="center">
  <a href="https://github.com/judgekeeper/judgekeeper">
    <img src="banner.png" alt="judgekeeper: Check your LLM-as-a-judge. See how often it agrees with human labels, in one command." width="820">
  </a>
</p>

## Check your LLM-as-a-judge.

See how often it agrees with human labels, in one command.

An LLM-as-a-judge is an AI model that grades the answers of another AI model. **judgekeeper** shows how often your judge agrees with your own Pass or Fail marks, so you can decide whether to rely on it. It is free and open source, and it runs on your own computer.

```
cd your-project
pip install judgekeeper
judgekeeper start
```

Run it in your project's own Python environment. It reads the results your eval tool already saved.

- **Code:** [judgekeeper/judgekeeper](https://github.com/judgekeeper/judgekeeper)
- **Website:** [www.judgekeeper.com](https://www.judgekeeper.com)
- **Package:** [pypi.org/project/judgekeeper](https://pypi.org/project/judgekeeper/)
