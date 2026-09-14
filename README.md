# Business & Statistical Analytics Case Studies

A collection of independent analytics case studies from UC San Diego coursework. Each is a standalone project from a different course — grouped here as a single repo since each exists only as a write-up (no separate code file).

---

## 📁 `spam-classification/`
**Course:** Math 189
**File:** `math189_spam_classification.pdf`

Compared standardized, log-transformed, and discretized encodings of the UCI Spambase dataset (visualized via PCA and t-SNE), then benchmarked 7 classification methods — logistic regression, LDA, QDA, linear & RBF-kernel SVM, decision tree, random forest, and bagging — across all three encodings. Used Bayesian hyperparameter optimization (`mlrMBO`) to tune a random forest, reaching **2.5% test error**, the best result of any method tried.

**Tools:** R (MASS, e1071, randomForest, rpart, Rtsne, mlr, mlrMBO, DiceKriging, rgenoud)
**Skills:** model benchmarking/comparison, dimensionality reduction (PCA, t-SNE), Bayesian hyperparameter optimization, statistical/machine learning, feature-transform selection

---

## 📁 `rsa-televisions/`
**Course:** MGT 171R, Group 25
**Files:** `rsa_televisions_executive_summary.pdf`, `rsa_televisions_slides.pdf`

Advised a TV manufacturer's COO on inventory strategy during a supply shock (labor shortages, a 15% storage-cost spike, ocean-freight delays). Used EOQ and safety-stock formulas to set reorder points and shipment sizes for both a short-term (elevated lead time, ~9,000-unit reorder trigger) and long-term (recovered lead time, ~2,700–3,000-unit reorder point) scenario, and made the case for maintaining — rather than exiting — the company's primary retail partnership (Womart, ~$18.75M/year), with a phased short/mid/long-term operational roadmap.

**Tools:** EOQ modeling, safety-stock (z·σ) analysis, case-based strategy
**Skills:** inventory management modeling, risk analysis, scenario planning, executive communication/case writing

---

## 📁 `er-games/`
**Course:** MGT 151, Group 2
**File:** `er_games_sales_strategy.pdf`

Three-part analytics engagement on video game sales data: (1) regression showed critic score, not user score, significantly predicts North American sales (p = 0.0335); (2) A/B testing across regions found Europe — not Japan — as the strongest secondary market after North America; (3) hierarchical and k-means clustering on sales, platform, genre, and rating data suggested a strategic pivot from strategy games toward sports titles.

**Tools:** JMP, regression, A/B/hypothesis testing, clustering
**Skills:** regression analysis, A/B/hypothesis testing, unsupervised clustering, data-driven strategic recommendation, business presentation
