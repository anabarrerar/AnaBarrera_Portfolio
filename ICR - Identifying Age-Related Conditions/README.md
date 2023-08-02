<h1>ICR - Identifying Age-Related Conditions</h1>

The competition data comprises over fifty anonymized health characteristics linked to three age-related conditions. The goal is to predict whether a subject has or has not been diagnosed with one of these conditions -- a binary classification problem.

**`train.csv`** - The training set has 617 rows, 58 columns

* `Id:` Unique identifier for each observation.

*  `AB-GL:` Fifty-six anonymized health characteristics. All are numeric except for EJ, which is categorical and binomial.

*  `Class:` A binary target, 1 indicates the subject has been diagnosed with one of the three conditions, 0 indicates they have not.

**`test.csv`** - The test set The goal is to predict the probability that a subject in this set belongs to each of the two classes.

**`greeks.csv`** - Supplemental metadata, only available for the training set. 617 rows, 6 columns

* `Alpha:` Identifies the type of age-related condition, if present. *A:* No age-related condition. Corresponds to class 0. *B, D, G:* The three age-related conditions. Correspond to class 1.

* `Beta, Gamma, Delta:` Three experimental characteristics.

* `Epsilon:` The date the data for this subject was collected. Note that all of the data in the test set was collected after the training set was collected.

<h2>Skills</h2>
