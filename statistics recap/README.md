SciPy:
- one-sample t-test: tval, pval = ttest_1samp(a,b)
- two-sample t-test: tval, pval = ttest_ind(a,b)
- binomial test: pval = binom_test(a, b, samplesizepercentage, alternative='...')
- one way anova: fstat, pval = f_oneway(a, b, c)
- tukey's range test: pairwise_tukeyhsd(a, b, alpha)
- chi-square: table = pd.crosstab(variable_1, variable_2) chi2, pval, dof, expected = chi2_contingency(table)

One-sample t-tests are used for comparing a sample mean to an expected population mean

Two Sample T-Tests (for an association between a quantitative variable and a binary categorical variable)

Binomial test for binary data and want to compare a sample proportion/frequency to an underlying probability (population value)

ANOVA and Tukey Tests (for an association between a quantitative variable and a non-binary categorical variable). After you have run an ANOVA and found significant results, then you can run Tukey’s HSD to find out which specific groups’s means (compared with each other) are different. The test compares all possible pairs of means.

Chi-Square Tests (for an association between two categorical variables)
