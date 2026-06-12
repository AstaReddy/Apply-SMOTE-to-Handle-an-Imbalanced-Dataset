# Apply-SMOTE-to-Handle-an-Imbalanced-Dataset


# Findings:
#
# The original dataset was highly imbalanced, with fraud
# transactions representing a very small percentage of
# the total samples.
#
# SMOTE was applied only to the training dataset to
# synthetically generate minority-class samples and
# balance the class distribution.
#
# After training Random Forest models on both the
# original and SMOTE-resampled datasets, the model
# trained with SMOTE achieved higher recall on the
# minority (fraud) class.
#
# This indicates that SMOTE improved the model's
# ability to detect fraudulent transactions, which
# is critical in highly imbalanced classification
# problems.
