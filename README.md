# QSAR-model-for-pIC50-value-prediction

The IC50 value is an important measure of a drug's potency and selectivity, which are key factors to consider in drug design. Potency refers to the amount of drug required to achieve a certain level of inhibition of the target protein or enzyme, and a more potent drug is generally considered more desirable as it is likely to have fewer side effects and may be more effective at lower doses.
Selectivity refers to the ability of a drug to specifically target the intended protein or enzyme and not non-target proteins or enzymes, which is important as it helps to minimize side effects and increase efficacy. In general, a more potent drug is more likely to be more selective as it requires a lower concentration to achieve a given level of inhibition of the target protein or enzyme. This means that at lower concentrations, the drug is more likely to bind specifically to the intended target, rather than binding to non-target proteins or enzymes. The lower the concentration required to achieve a certain level of inhibition, the more selective the drug is likely to be. Therefore, the drug with the lowest IC50 value is more likely to be more selective than other drugs with higher IC50 values.

In my project I predicted the pIC50 values given just the smile structure for a compound.I extracted molecular descriptors from the given smile structures and trained my model to predict the respective pIC50 Values. I extraxted the compounds having pIC50 value from the train set and predicted their pIC50 value.
