Inspired by Dr.Chen's work on ethical ML in healthcare, I analyzed gender representation and model performance in a public health fitness dataset.

I found evidence of differential performance and missing variables relevant to women’s physiology, which reinforced my interest in research at the intersection of women’s health and ethical AI.”

Details:

1️⃣ Observation / result

Data-level:

Female participants: 951 (train), 403 (test)

Male participants: 988 (train), 428 (test)

True obesity rate: Female 42.8%, Male 37.6%

Model-level:

Logistic regression accuracy: Female 64.0%, Male 67.5%

2️⃣ Interpretation (research insight)

Despite balanced representation and simple fitness features, the model predicts less accurately for women.

Features like minutes of activity and sedentary time fail to capture women-specific physiological context (e.g., hormonal cycles, metabolic differences).

This mirrors Dr.Chen’s point:

“Bias in health ML often comes not from algorithms themselves, but from what data is collected (or missing) and how problems are framed.”

3️⃣ Conclusion

“Even in a public fitness dataset with roughly equal representation, a standard predictive model performs worse for women. This highlights how current fitness and health data systematically overlook women-specific physiology, producing inequitable ML outcomes — exactly the type of structural bias addressed in ethical ML research.”