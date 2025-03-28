Can be used to prevent overfitting

Comparison to Regression - All three criteria evaluate models while balancing fit quality against model complexity, thus assisting in selecting optimal and parsimonious models that generalize well beyond the training data.

Adjusted R-squared:
Adjusts the standard R-squared by accounting for the number of predictors. It prevents artificial inflation of R-squared as more predictors are added.

AIC and BIC:
These metrics balance goodness-of-fit against complexity. Lower values indicate better models, penalizing overly complex models to reduce overfitting. BIC imposes a stronger penalty compared to AIC, thus preferring simpler models more aggressively.

But in ML, we want to do things a bit differently. All these above metrics are obtained after the model is built
