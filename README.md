# burnin-latent-defect-screening
Machine learning project for screening latent defects in burn-in test data
## Key findings

### UCI SECOM
- The dataset has 1,567 examples and 590 measurement features. It contains 1,463 passes and 104 failures, with many missing measurements.
- In an exploratory 40-feature model, a 0.30 cutoff caught 80 of 104 failures but also flagged 705 passing examples. This shows a tradeoff between catching failures and false alarms.

### Electrolytic capacitor data
- Across the 10 V, 12 V, and 14 V datasets, the stored measurement value near 100 Hz generally decreased as test time increased.
- This is an exploratory pattern: the measurement’s physical meaning and units are unconfirmed, and the data does not provide confirmed good/fail labels.

### Limitations
These analyses do not establish a validated defect-screening method or threshold. Further work needs verified labels, confirmed measurement meanings, and evaluation on separate data.