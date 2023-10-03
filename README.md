# pandas-challenge

Tutor Assistance:

I was having a lot of trouble with this section because I was incorrectly using pd.cut and the tutor helped stear me in the right direction to make my code functional:

# Use `pd.cut` to categorize spending based on the bins.
school_spending_df["Spending Ranges (Per Student)"] = pd.cut(per_school_capita, bins=spending_bins, labels=labels)
school_spending_df
