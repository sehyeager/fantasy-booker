## Progress Report

 - Data is fully in hand!  
 - Full EDA is not complete:  will be doing so within jupyter notebooks and pandas.
 - I ran two preliminary models: one linear regression, one random forest.  Pretty awful r2 scores.
 - Blockers:  treating every wrestler as a feature makes our data extremely feature heavy for the # of feuds we have.
 - Timeline: complete EDA (examine distributions, imbalances, account for them).  I also need to be able to use my model to predict scores for a 3 month period, given a list of roster participants (only select wrestlers who are found in the database.)
 - My topic has not changed, but I think I may need to change my problem statement.  Many of the wrestlers in my database are retired/dead, and even more do not currently wrestle for the same promotion.  It would not be feasible to build a season from an existing roster due to this.  Instead, perhaps I can use this to help build a 'greatest hits' playlist for WWE's streaming service?