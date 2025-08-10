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

### 3.3 Copilot (2025-07-22, Version Unspecified)

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

- Data: cuse.com, Syracuse University Women’s Basketball (2024-25)
- LLM analysis: ChatGPT-4.1, Gemini 2.5 Pro, Copilot (2025-07-22)

---

## 8. Extended Comparative Analysis — GPT-5 vs Gemini 2.5 Pro vs Copilot

This section extends the original Task 05 analysis by adding derived performance metrics, calculated directly from the dataset, and comparing how each LLM handled them.

### 8.1 Derived Team Performance Metrics

| Metric | Ground Truth (calculated) | GPT-5 | Gemini 2.5 Pro | Copilot |
|--------|---------------------------|-------|----------------|---------|
| **Average Point Differential (Season)** | –0.9 PPG | Matched | Matched | Matched |
| **Average Point Differential (Conference)** | –6.3 PPG | Matched | Matched | –6.2 (rounding diff) |
| **Best Win Margin** | +35 vs Dartmouth (87–52) | Correct | Correct | +24 vs Niagara (incorrect) |
| **Smallest Win Margin** | +5 vs Miami (FL) | Correct | Correct | Correct |
| **Home Avg Point Differential** | +5.3 PPG | Correct | +5.3 | ~+1.0 (incorrect) |
| **Away Avg Point Differential** | –9.5 PPG | Correct | –10.5 (close) | ~–7.0 (incorrect) |

**Observation:**  
- GPT-5 and Gemini were generally accurate on derived stats, with Gemini’s away differential slightly off due to possible rounding or grouping.
- Copilot’s “Best Win Margin” and home/away differentials diverged from computed values, likely due to simplified or incorrect internal calculations.

---

### 8.2 Individual Player Metrics (min. 50 attempts for 3PT%)

**3-Point Percentage Leaders**
| Player | 3PT% | GPT-5 | Gemini 2.5 Pro | Copilot |
|--------|------|-------|----------------|---------|
| Sophie Burrows | 39.6% | ✓ | ✓ | ✓ |
| Georgia Woolley | 34.1% | ✓ | ✓ | ✓ |
| Dominique Camp | 32.7% | ✓ | ✓ | ✓ |
| Madeline Potts (48 att.) | 37.5% | Below threshold | Below threshold | Listed but noted below threshold |

**Assist-to-Turnover Ratio Leaders**
| Player | A/T Ratio | GPT-5 | Gemini 2.5 Pro | Copilot |
|--------|-----------|-------|----------------|---------|
| Dominique Camp | 2.21 | ✓ | ✓ | ✓ |
| Olivia Schmitt | 1.56 | ✓ | ✓ | ✓ |
| Angelica Velez | 1.24 | ✓ | ✓ | ✓ |
| Georgia Woolley | 1.04 | Mentioned as 4th | Not listed | Listed |

**Observation:**  
- All three models aligned on leaders meeting thresholds, but Copilot occasionally included players slightly below the defined cut-off (e.g., Potts) or expanded the list to marginal cases (e.g., Woolley in A/T).

---

### 8.3 “Most Improved Player” Handling

| Model | Response | Comment |
|-------|----------|---------|
| GPT-5 | Explicitly stated cannot determine without prior season stats | Statistically correct |
| Gemini 2.5 Pro | Same as GPT-5, noted need for year-over-year comparison | Statistically correct |
| Copilot | Named Georgia Woolley based on current-season volume and minutes | Subjective assumption, not meeting improvement definition |

**Observation:**  
GPT-5 and Gemini adhered to a rigorous data requirement. Copilot’s approach was faster but not statistically robust.

---

### 8.4 Interpretation of “Most Impressive / Toughest” Win

- **GPT-5:** Provided both smallest-margin win (Miami +5) and a quality-context win (Virginia Tech road win).
- **Gemini:** Highlighted Virginia Tech win with detailed game context.
- **Copilot:** Chose Missouri win (82–59) as “strongest opponent defeated,” implying an opponent-strength criterion without explicit ranking data.

**Observation:**  
This illustrates how LLMs interpret subjective terms differently if the prompt does not define evaluation criteria.

---

### 8.5 Key Takeaways from Extended Comparison

1. **Numerical Accuracy:** GPT-5 and Gemini were more precise on derived calculations; Copilot occasionally deviated.
2. **Threshold Handling:** GPT-5 and Gemini respected defined stat thresholds; Copilot sometimes included marginal cases.
3. **Analytical Rigor:** GPT-5 and Gemini flagged missing data for improvement metrics; Copilot filled the gap with an assumption.
4. **Narrative vs Modular Style:**  
   - GPT-5: Modular Q&A plus analytical notes  
   - Gemini: Cohesive narrative summary  
   - Copilot: Bullet-point brevity, faster but with occasional factual variance
5. **Subjectivity in “Impressive Wins”:** Varies greatly unless prompt specifies evaluation criteria.

---

### Credits for Extended Analysis
- **Data Source:** 2024–25 Syracuse University Women’s Basketball official cumulative statistics and game log  
- **LLMs Compared:** GPT-5 (OpenAI), Gemini 2.5 Pro (Google, July 2025), Copilot (Microsoft, generated Aug 10, 2025; version unspecified) 
