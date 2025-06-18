# 🧠 Pipistrel.io AI Crossword Benchmark
*Can AI handle human-level wordplay? Let's find out.*

This project benchmarks different AI models by having them solve the **New York Times Mini Crossword** daily.

## 🔍 Why?
LLMs are great with facts and reasoning — but how well do they do with puns, wordplay, and lateral thinking?

## 📦 Structure

| Folder | Purpose |
|--------|---------|
| `crossword_solver/` | Scripts for each model's solving logic |
| `data/daily_puzzles/` | Daily crossword clues and layout |
| `results/` | Model answers and scoring results |
| `logs/` | Manual notes or experiment logs |
| `notebooks/` | Optional analysis and visualisation tools |
| `utils/` | Shared tools for formatting, scoring, etc. |

## 🤖 Models Tested
- OpenAI ChatGPT (GPT-4)
- Google Gemini (NotebookLM)
- Anthropic Claude
- More to come...

## 📊 Example Result
🗓️ Puzzle: 2025-06-18
Clue: "Cold cube" → AI Guess: ICE ✅
Clue: "___-do-well" → AI Guess: NEER ❌ (Correct: NE'ER)

ChatGPT: 9/10
Gemini: 8/10
Claude: 10/10

## 🚀 Roadmap
- [ ] Automate puzzle input
- [ ] Add leaderboard view
- [ ] Post weekly wrap-ups to LinkedIn & Instagram
- [ ] Create web-friendly archive for results

## 💡 Follow Along
**🔗 [Pipistrel.io on Instagram]()**  
**🔗 [Pipistrel.io on LinkedIn]()**

*Built with curiosity by Ruth @ Pipistrel.io*
