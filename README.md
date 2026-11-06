# LaDarius Jackson

Business analytics and applied data for finance decisions. B.B.A. in Business Analytics & Information Systems, Computer Science minor, at the University of Mississippi (Ole Miss). Expected May 2027. Olive Branch, Mississippi.

**Portfolio:** [ladariusjackson1.github.io](https://ladariusjackson1.github.io/)

Tax preparer and QuickBooks ProAdvisor. Founder of Double Eagle Financial LLC, a small-business bookkeeping practice. Also builds talking-website samples for local contractors on Go High Level. The studies below are educational work on public files. They are not a job, a client book, or a production loss model.

## Flagship studies

Headline dollars are a published cost matrix or a stated planning scenario. They are a way to score a cutoff, not cash collected and not a lender’s profit and loss. The three repositories name Streamlit app URLs. On 6 Nov 2026 each of those URLs redirected an unauthenticated request to a Streamlit sign-in page, so this profile links the code only.

### [credit-risk-prediction](https://github.com/ladariusjackson1/credit-risk-prediction)

Educational study of the 1994 Statlog German Credit file (OpenML `credit-g`, 1,000 installment applicants). Histogram gradient boosting was selected on training-fold ROC-AUC (0.793 ± 0.054). On the locked 200-applicant holdout its ROC-AUC is 0.772. A cutoff of 0.15, fit on training scores only, books 56 applicants and 5 defaults (8.9% inside the booked loans, against a 30% base rate). Illustrative cost under the Statlog 5:1 matrix, at $200 a unit, is $22,800, against $60,000 for approving everyone.

Tech: Python, pandas, scikit-learn

### [loan-approval-prediction](https://github.com/ladariusjackson1/loan-approval-prediction)

Educational study of a public Lending Club sample (OpenML 43729, 9,578 loans). Logistic regression is the deployed model, chosen on cross-validated ROC-AUC (0.670 ± 0.015). After isotonic calibration fit on training out-of-fold scores, holdout ROC-AUC is 0.703 (95% interval 0.674 to 0.734). At the calibrated cutoff of 0.89, 415 of 437 approvals on the 1,916-loan holdout were fully paid (94.9%). Under a planning scenario of $5,000 for a false approval and $600 for a false decline, that book costs $139,000 less than declining everyone.

Tech: Python, pandas, scikit-learn

### [fraud-detection-ml](https://github.com/ladariusjackson1/fraud-detection-ml)

Educational review-queue study of the public OpenML credit-card file (data id 1597; 275,663 rows after exact duplicates are removed, 473 frauds). A random forest chosen on validation cost reviews 76 of 95 test frauds and pulls 25 legitimate tickets, about 18.3 reviews per 10,000 transactions. Test PR-AUC is 0.679 (95% interval 0.579 to 0.788). Planning cost on that test slice is $6,411, against $17,315 for approving every transaction. The write-up’s stated gap is $10,903, and the 95% interval on the test cost is $2,102 to $12,180. Review fees, the false-decline penalty, the chargeback fee, and the 1.10 dollars-per-euro rate are planning inputs. An undersampled logistic regression has a lower test cost and was not selected.

Tech: Python, pandas, scikit-learn

## Revenue model

[revenue-prediction-model](https://github.com/ladariusjackson1/revenue-prediction-model) is a separate set of studies plus a local Double Eagle planning dashboard. The daily-sales study is a finished forecast on the UCI Online Retail series. A random forest chosen on an earlier window has holdout MAE of £11,629.44 for 1 Oct–8 Dec 2011, about £654 below a same-weekday-last-week forecast (£12,283.78). That is one UK gift retailer and one holiday window, not a Double Eagle result. Projects 02–07 train on synthetic data and do not publish a headline score in the repository README. The repository does not name a public demo URL.

Tech: Python, pandas, scikit-learn

## Also

[double-eagle-financial-site](https://github.com/ladariusjackson1/double-eagle-financial-site) is the static source for the bookkeeping marketing site. On 6 Nov 2026, `doubleeaglefinancial.com` and `www.doubleeaglefinancial.com` returned HTTP 404.

## Tools

Python · pandas · scikit-learn · Streamlit · HTML/CSS/JavaScript · QuickBooks Online
