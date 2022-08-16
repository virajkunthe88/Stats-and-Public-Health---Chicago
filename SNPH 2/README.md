
Class Project for Brainstation - The city of Chicago, Illinois has been keeping track of mosquito populations and WNV prevalence using a series of traps that they place around the city. They are then able to study the captured specimens and monitor the state of WNV spread in the city.

You are given mosquito tracking data from 2008 to 2019.

For this deliverable, you must use the provided cleaned dataset which differs from that for Part 1.

----------------------------------------------------------------------------------------
Answer a few business questions based on the usage data provided


Part 1 - Basic Analysis

    Convert the WNV Present column into a binary column and create dummy variables from the Trap type column.

    What is the average number of mosquitoes for each month? What trends do you notice?

Part 2 - Statistical Analysis

    Is there a statistically significant difference between the different mosquito species when looking at the occurrence of West Nile Virus?

    Which columns are positively correlated with the number of mosquitoes caught? Which columns are negatively correlated? Are these correlations statistically significant?

Part 3 - Advanced Statistical Analysis

    Run a linear regression to determine how the independent variables affect the number of mosquitoes caught. Explain your model construction process. Analyze the model and the results and discuss the model’s limitations. This may end up being an iterative process.
    Note:
        You will likely see a low R^2 value, that is to be expected.
        This dataset does not respond well to performing VIF analysis, so this is not required.
        WNV Present must not be one of your independent variables.

    Run a logistic regression to determine how the independent variables affect West Nile Virus presence. Explain your model construction process. Analyze the model and the results and discuss the model’s limitations. This may end up being an iterative process.
    Note: Mosquito number should be one of your independent variables.


----------------------------------------------------------------------------------------

SNPH_2_VIRAJ_KUNTHE.ipynb

- Code required to answer the above questions.

mosquito_data_part_2.csv

- Provided clean data.

