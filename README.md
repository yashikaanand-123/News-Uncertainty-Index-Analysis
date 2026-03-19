# News-Uncertainty-Index-Analysis

# NYT Headlines Uncertainty & Sentiment Analysis (Feb–Mar 2021)

End-to-end data analysis project that turns raw news headlines into meaningful insights.

### What I built
- Daily **Covid Uncertainty Index** (fraction of headlines mentioning Covid/vaccine/stimulus)
- Daily **Economic Policy Uncertainty Index** (coarse version using policy keywords)
- Collocation detection + TF-IDF + day-to-day similarity heatmap
- VADER sentiment analysis on Covid-related articles
- Correlation analysis with S&P 500 daily returns

### Key Findings
- Covid uncertainty peaked in early/mid-March around the $1.9T stimulus bill and vaccine rollout.
- Sentiment was strongly neutral (0.834) with low positive (0.056) and moderate negative (0.109) tone.
- Weak positive correlation between Covid news volume and stock returns during this period.

### Technologies used
- Python, pandas, scikit-learn, gensim (Phrases), NLTK VADER
- TF-IDF vectorization with collocations
- Matplotlib/Seaborn visualizations

### Skills demonstrated
Text processing • Feature engineering • Time-series analysis • Sentiment analysis • Correlation analysis
