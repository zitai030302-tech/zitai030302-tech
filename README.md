# Hi, I'm Zitai Li

我正在准备互联网算法相关实习，关注 **machine learning systems, data-driven modeling, recommender/search algorithms, and algorithm engineering**。

I like building projects where models are connected with real data, reproducible evaluation, and usable engineering workflows.

## Focus

- **Machine Learning:** feature engineering, regression/classification, model evaluation, cross-validation, leakage checks
- **Recommendation / Search:** retrieval, ranking, offline metrics, candidate generation, lightweight serving
- **Algorithm Engineering:** backtesting, risk control, data pipelines, experiment runners, dashboards, tests
- **Research Reproduction:** reading papers, modernizing legacy code, validating metrics, documenting assumptions

## Featured Projects

### [QuantDesk](https://github.com/zitai030302-tech/quantdesk)

Event-driven crypto strategy research sandbox with backtesting, paper trading, risk control, SQLite persistence, and dashboard monitoring.

- Built a modular runtime covering market data ingestion, strategy execution, paper trading, risk control, persistence, and dashboards.
- Implemented strategy registry, technical indicators, backtesting metrics, order validation, and Freqtrade-style CLI compatibility.
- Added unit and integration tests for trading flow, risk rules, REST clients, order validators, strategy behavior, and dashboard logic.

**Tech:** Python, pandas, SQLite, WebSocket, pytest

### [Graphene BP Reproduction](https://github.com/zitai030302-tech/graphene-bp-reproduction)

Modern feature-level reproduction of a Bio-Z blood-pressure estimation pipeline.

- Modernized a published research workflow for current pandas/scikit-learn versions.
- Reproduced subject-specific AdaBoost regression experiments for SBP/DBP from pre-extracted Bio-Z features.
- Compared faithful preprocessing with a safer train-only imputation variant to analyze possible data leakage.

**Tech:** Python, pandas, scikit-learn, AdaBoost, experiment design, model evaluation

## Currently Building

### Recommender System Lab

An end-to-end recommendation project covering retrieval, ranking, offline evaluation, and lightweight serving.

- Popularity, ItemCF, matrix factorization, two-tower retrieval, and ranking baselines
- Metrics: Recall@K, NDCG@K, MAP, AUC, coverage, diversity
- Demo: query a user and return Top-K recommendations with recall source and ranking score

## Looking For

我希望参与推荐、搜索、广告、风控、数据挖掘等方向的算法实习，尤其喜欢 **模型 + 数据 + 工程落地** 结合紧密的工作。

## Contact

- GitHub: [@zitai030302-tech](https://github.com/zitai030302-tech)

