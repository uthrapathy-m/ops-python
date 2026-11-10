# ops-python

Small Python tools for everyday DevOps work. I'm building them while learning Python, as Phase 1 of my [DevOps to AI infrastructure roadmap](https://uthrapathy-m.github.io/devops-to-ai-infra/).

## Tools

| Tool | Week | What it does | Status |
|---|---|---|---|
| `tools/restarts.py` | W1 | Lists pods that restart often, with namespace and threshold flags, and exports a CSV | Planned |
| `tools/ec2_spend.py` | W2 | Shows EC2 spend grouped by tag, using Cost Explorer | Planned |
| `log-summarizer/` | W3 | FastAPI service that summarizes logs with an LLM and reports token usage | Planned |
| `tools/vram.py` | W4 | Estimates the GPU memory a model needs | Planned |

## Setup

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate    macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
```

## What I learned

I'll add three notes here each week.

### Week 1
- 
