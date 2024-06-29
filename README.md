# OIBSIP-Sales-Prediction
![image](https://github.com/lekshmiiyyer/OIBSIP-Sales-Prediction/assets/108746697/db739bf8-acc3-473d-acf8-bd27d662f082)

# Insights 
From the pairplot visualization, we can derive several insights into the relationships between the advertising channels (`TV`, `Radio`, `Newspaper`) and `Sales`. Here are some observations:

### Key Insights

1. **TV vs Sales:**
   - The scatter plot for `TV` and `Sales` shows a strong positive linear relationship. This means that as the expenditure on TV advertising increases, the sales also tend to increase.
   - This indicates that TV advertising has a significant impact on sales.

2. **Radio vs Sales:**
   - The scatter plot for `Radio` and `Sales` shows a moderate positive relationship. Although the correlation is not as strong as with TV, it still suggests that increasing the radio advertising budget generally leads to higher sales.
   - There is more scatter in this plot compared to the `TV` and `Sales` plot, indicating some variability in the effect of radio advertising on sales.

3. **Newspaper vs Sales:**
   - The scatter plot for `Newspaper` and `Sales` shows a weak positive relationship. This suggests that newspaper advertising has a lesser impact on sales compared to TV and Radio.
   - The points are more dispersed, indicating that spending on newspaper advertising does not consistently lead to increased sales.

4. **Relationships Among Advertising Channels:**
   - The scatter plots between `TV` and `Radio`, `TV` and `Newspaper`, and `Radio` and `Newspaper` show no clear relationship. This indicates that the budgets for these different advertising channels are likely set independently of each other.

5. **Histograms:**
   - The histograms along the diagonal show the distribution of each variable.
   - The `TV` budget is relatively uniformly distributed.
   - The `Radio` and `Newspaper` budgets have right-skewed distributions, indicating that lower values are more common.
   - The `Sales` histogram shows a fairly normal distribution, with most sales values clustering around the mean.

- **TV advertising** has the most substantial impact on sales, as evidenced by the strong positive linear relationship.
- **Radio advertising** also positively affects sales, but to a lesser extent and with more variability.
- **Newspaper advertising** shows the weakest correlation with sales, suggesting it may not be as effective as the other channels in driving sales.
- The independence of budgets among `TV`, `Radio`, and `Newspaper` implies that businesses might consider reallocating their advertising budgets based on the effectiveness of each channel, with a focus on TV for maximum sales impact.

# RESULT 
Results Table:
               Model      RMSE       R^2
0  Linear Regression  0.642581  0.986918
1              Ridge  0.636045  0.987183
2              Lasso  0.909664  0.973783
3      Random Forest  0.570939  0.989673
4  Gradient Boosting  0.564023  0.989921

Best Model: GradientBoostingRegressor(n_estimators=200)
Best RMSE: 0.5640232321263566
Best R^2: 0.9899212298543076

