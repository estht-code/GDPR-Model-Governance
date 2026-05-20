# GDPR-Model-Governance
Key points

1. GDPR → Pricing Models (what you must think about)
✅ A. Lawful basis for using data
You can’t just use any data in a model—you need a legal justification.
Typical bases in pricing:

Contract → pricing needed to provide insurance/product
Legitimate interest → business needs vs customer impact

👉 Example:

✔ Using claims history → clearly needed
❌ Using social media behaviour without clear justification


✅ B. Fairness in modelling (closely tied to your earlier question)
GDPR says data must be used fairly, meaning:

No unexpected or harmful uses of data [ico.org.uk]
No unjustified adverse impact on individuals

In pricing terms:

Watch for proxy variables

e.g. postcode → may indirectly reflect ethnicity or income


Ensure outcomes are:

Justifiable
Not discriminatory



👉 Real interview point:

“I would assess whether model features introduce unintended bias or proxy discrimination, and ensure any differences in pricing are risk-based and justifiable.”


✅ C. Transparency (very important for models)
Under GDPR, you must be clear and open about how data is used [ico.org.uk]
In practice:

Customers should understand:

What data is used
Why it affects their price


Internally:

Full documentation
Clear model logic



Model implication:

Avoid overly complex “black box” models unless you can explain them
Be ready to explain:

Feature importance
Pricing drivers



👉 Example:

✔ GLM with clear rating factors
⚠️ Complex ML model → needs explainability tools (e.g., SHAP)


✅ D. Data minimisation
You should only use data that is necessary [gdpreu.org]
In pricing:

Don’t include variables “just in case”
Each feature should:

Add predictive value
Have a clear purpose



👉 Interview angle:

“I’d ensure variables are included only if they improve model performance and can be justified from both a business and regulatory perspective.”


✅ E. Automated decision-making & profiling
This is a big one for pricing models.
GDPR gives individuals rights when decisions are:

Fully automated
Significantly affect them (e.g. price offered) [gov.uk]

Requirements:

Explain decisions
Allow human review (in some cases)
Justify logic

👉 Example:

Price generated entirely by a model = “profiling”
You need:

Explainability
Governance
Controls




🏗️ 2. GDPR → Model Governance (how models are controlled)
GDPR feeds directly into model governance frameworks.
✅ A. Documentation
You must clearly document:

Data sources
Assumptions
Model logic
Limitations

👉 Why:

Supports transparency
Enables audits


✅ B. Validation & monitoring
You need to check:

Model performance
Bias / fairness issues
Stability over time

👉 Example checks:

Segment-level pricing consistency
Disparate impact analysis


✅ C. Explainability
You must be able to:

Explain outputs to:

Regulators
Internal stakeholders
Sometimes customers



This links strongly to:

Transparency
Consumer protection


✅ D. Data governance & security
GDPR requires:

Secure handling of personal data
Protection against misuse or breaches [gov.uk]

In modelling:

Control access to datasets
Anonymise/pseudonymise where possible
Avoid unnecessary personal detail


⚖️ 3. Key trade-offs (this is what interviewers love)


AreaTension
Accuracy vs FairnessMore predictive variables may introduce bias
Complexity vs TransparencyAdvanced models harder to explain
Business vs GDPRMore data can improve pricing but may violate minimisation


















AreaTensionAccuracy vs FairnessMore predictive variables may introduce biasComplexity vs TransparencyAdvanced models harder to explainBusiness vs GDPRMore data can improve pricing but may violate minimisation
👉 Strong answer:

“I focus on balancing model performance with regulatory requirements, ensuring models are explainable, fair, and use only necessary data.”


💬 4. Strong “interview-ready” answer
If asked:
“How does GDPR affect pricing models?”
You can say:

GDPR impacts pricing models by requiring that personal data is used lawfully, fairly, and transparently. In practice, this means ensuring features are justified and not introducing bias, limiting data to what is necessary, and maintaining clear documentation and explainability. It also requires governance around automated decision-making, including the ability to explain and validate model outputs.


🎯 Quick takeaway
GDPR in modelling =
✅ Use data responsibly
✅ Avoid bias
✅ Be explainable
✅ Justify everything

If you want, I can turn this into specific bullet points for your CV or mock interview answers tailored to pricing roles at insurers/banks.
