# 🧠 Pipistrel.io AI Crossword Benchmark
*Can AI handle human-level wordplay? Let's find out.*

This project benchmarks different AI models by having them solve the **New York Times Mini Crossword** daily. Each model gets the same clues and layout, and we compare:

- ✅ **Accuracy** (how many answers it gets right)
- ⏱️ **Speed** 
- 🧠 **Reasoning quality** (optional notes)

---

## 🔍 Why?

LLMs are great with facts and reasoning — but how well do they do with puns, wordplay, and lateral thinking? This benchmark uses a fun, consistent test (the NYT Mini) to explore model capabilities in a constrained, human-like task.

---

## 📦 Structure

| Folder | Purpose |
|--------|---------|
| `crossword_solver/` | Scripts for each model's solving logic |
| `data/daily_puzzles/` | Daily crossword clues and layout |
| `results/` | Model answers and scoring results |
| `logs/` | Manual notes or experiment logs |
| `notebooks/` | Optional analysis and visualisation tools |
| `utils/` | Shared tools for formatting, scoring, etc. |

---

## 🤖 Models Tested

- OpenAI ChatGPT (GPT-4)
- Google Gemini (NotebookLM)
- Anthropic Claude
- More to come...

---

## 🧩 How it Works

1. **Input the puzzle**: Manually or via script.
2. **Send clues to each AI** using a consistent prompt.
3. **Collect answers** and log:
   - Total correct
   - Errors
   - Reasoning quality
4. **Track performance** over time.


## 🚀 Roadmap

- [ ] Automate puzzle input
- [ ] Add leaderboard view
- [ ] Post weekly wrap-ups to LinkedIn & Instagram
- [ ] Create web-friendly archive for results

---

## 💡 Follow Along

Daily results, insights, and behind-the-scenes commentary shared via:

**🔗 [Pipistrel.io on Instagram]()**  
**🔗 [Pipistrel.io on LinkedIn]()**  

---

*Built with curiosity by Ruth @ Pipistrel.io*


