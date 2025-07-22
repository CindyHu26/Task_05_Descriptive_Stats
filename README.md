# Task_05_Descriptive_Stats

## Syracuse University Women’s Basketball 2024-25 Season  
### Descriptive Statistics with Multiple Large Language Models (LLMs)

---

## 1. Task Overview

This project investigates the descriptive and analytical capabilities of three Large Language Models (LLMs)—**ChatGPT-4.1**, **Gemini 2.5 Pro**, and **Copilot (2025-07-18)**—using the 2024-25 Syracuse University Women’s Basketball team data as a case study.  
We present each model with the same dataset and prompts, then compare their responses for accuracy, reasoning, and presentation style.

---

## 2. Data Source

- [Syracuse Women’s Basketball Official Stats (2024-25)](https://cuse.com/sports/womens-basketball/stats/2024-25)
- **Original data not included in this repo**
- Key statistics and game logs extracted from the official cuse.com cumulative PDF.

---

## 3. Multi-LLM Q&A and Summaries

### 3.1 ChatGPT-4.1 (OpenAI, 2025-07)

#### **Prompted Q&A (English):**

**Q1. How many games did this team win in the 2024-25 season? What was the home record?**  
A: The team won a total of **12 games** this season. Their home record was **8 wins and 8 losses**.

**Q2. Who was the leading scorer? Who had the highest rebounds per game?**  
A: Georgia Woolley (#05), 16.0 points per game (463 points); Kyra Wood (#22), 6.8 rebounds per game (191 rebounds).

**Q3. Which player had the highest three-point shooting percentage?**  
A: Sophie Burrows (#04), 39.6% (65/164).

**Q4. Who was the most improved player this year?**  
A: Cannot be determined with current data—requires previous season stats for comparison.

**Q5. Who had the highest assist-to-turnover ratio?**  
A: Dominique Camp (#24), 2.21 (117 assists / 53 turnovers).

**Q6. What was the opponent's average points per game? What was the toughest win for Syracuse?**  
A: Opponents averaged **71.4 points per game**.  
Toughest win by smallest margin: **66-61 vs. Miami (FL)** (Jan 12, 2025). Notably, a high-quality road win was **93-87 at Virginia Tech** (Feb 6, 2025).

---

### 3.2 Gemini 2.5 Pro (Google, 2025-07)

#### **Gemini-Generated Season Summary:**

**Team Performance**  
The team finished the season with an overall record of 12 wins and 18 losses. Their record at home was 8 wins and 8 losses.

**Individual Player Statistics**  
- Top Scorer: Georgia Woolley led the team in scoring with an average of 16.0 points per game.
- Top Rebounder: Kyra Wood was the team's leading rebounder, averaging 6.8 rebounds per game.
- Highest Three-Point Percentage: Sophie Burrows had the highest three-point shooting percentage, making 39.6% of her attempts.
- Highest Assist-to-Turnover Ratio: Dominique Camp had the best assist-to-turnover ratio on the team at 2.21, with 117 assists and 53 turnovers.

**Opponent and Game Analysis**  
- Opponent's Average Score: Opponents scored an average of 71.4 points per game against Syracuse this season.
- Most Impressive Win: While "toughest" can be subjective, a strong candidate for the most impressive win of the season was the 93-87 victory against Virginia Tech on February 6, 2025. This was a high-scoring road game against a tough opponent, played in front of a crowd of 4,902.

**Most Improved Player**  
To determine the most improved player, one would need to compare statistics from the previous season to the current season. Since the provided data only covers the 2024-25 season, it is not possible to definitively name a "most improved player" without more information.

---

### 3.3 Copilot (2025-07-18, Version Unspecified)

#### **Copilot-Generated Summary:**

**Team Performance**
- **Total Wins:** 12
- **Home Record:** 8–8
- **Opponent Average Score:** 71.4
- **Strongest Opponent Defeated:** Missouri on 11/25/24 with score 82–59

**Player Highlights**
- **Top Scorer:** Georgia Woolley – 463 points
- **Top Rebounder:** Kyra Wood – 191 rebounds
- **Best 3-Point Shooter:** Sophie Burrows – 39.6% (65/164)
- **Most Improved Player:** Georgia Woolley  
  _Criteria: High minutes (952), high scoring (463), and consistent performance across games._
- **Best Assist-to-Turnover Ratio:** Dominique Camp – 117 assists / 53 turnovers ≈ **2.21**

---

## 4. Comparative Analysis of LLM Responses

### Similarities
- **Descriptive Questions:** All three LLMs correctly identified wins, home record, individual stat leaders, and opponent average score.
- **Caveat for "Most Improved":** ChatGPT-4.1 and Gemini 2.5 Pro both explicitly noted that the "most improved player" cannot be determined without prior season data; Copilot made an assumption based only on high volume and performance in current year.

### Differences
- **Interpretation:**  
  - **Copilot** directly named Georgia Woolley as "most improved" based solely on this season's volume, which is not technically correct for "improvement" but provides a rationale.
  - **ChatGPT-4.1** and **Gemini 2.5 Pro** both provided more rigorous/statistically accurate disclaimers.
- **Presentation:**  
  - **ChatGPT-4.1** gave modular, question-by-question answers.
  - **Gemini 2.5 Pro** offered a narrative-style team summary.
  - **Copilot** provided bullet-point highlights and subjectively chose "strongest opponent defeated" (Missouri), while the other models highlighted margin or ranked win significance differently.

### LLM Limitations
- None of the models can truly measure "improvement" without year-over-year stats.
- Subjective questions (“strongest” or “toughest” win) are interpreted differently by each model.

---

## 5. Methodology & Recommendations

- **Prompt Engineering:**  
  All models were tested with both direct Q&A and narrative summary prompts.
- **Best Practices:**  
  - For accurate "most improved" analysis, always provide prior year data.
  - Clarify criteria for subjective categories when querying LLMs.
- **Further Steps:**  
  - Incorporate previous season’s stats for trend analysis.
  - Visualize data using scripts (not included here per assignment rules).
  - Experiment with other LLMs or updated model versions.

---

## 6. Usage

- Add further prompts and model comparisons in `prompt_and_answers.md`.
- Place scripts or code in `scripts/`.
- **Original dataset is not included per assignment instructions.**

---

## 7. Credits

- Project by [Your Name/Team]
- Data: cuse.com, Syracuse University Women’s Basketball (2024-25)
- LLM analysis: ChatGPT-4.1, Gemini 2.5 Pro, Copilot (2025-07-18)

---
