**Dylan**

Based on the plots and graphs, there is a positive correlation between alcohol and wine quality. If we look at the line plot, as alcohol percentage increases, so does the wine quality. This could be due to how alcohol content affects the wine's body. A higher alcohol content is usually associated with a richer and fuller texture, which is why it could be seen as higher quality. Moreover, if we compare the colors of the bars in each quality(from the countplot), we can see that as the wine quality increases, the colors start to shift towards the higher alcohol percentage's colors. While there are some lower alcohol percentages at those high wine quality ranges, the count is very low , so we can see it as outliers. The higher alcohol percentages have higher counts in higher wine quality values, which indicates that there indeed is a positive correlation between alcohol percentage and wine quality.Therefore, the plot above has shown that alcohol percentage does play a big part into determining the quality of the wine. (This is based on Dylan's EDA, so checkout Dylan's milestone2.ipynb in the analysis folder to see the plots that were mentioned here).

Moreover, we can see that as fixed acidity increases, the wine quality decreases. Looking at the lineplot, while there are some outliers, we can still see that there is an inverse correlation. Thus, this is another variable besides alcohol that is a big contributor to the quality of the wine. Similar to alcohol, we can see that as the quality of wine increases, the colors from the countplot seem to shift towards lower fixed acidity. When we remove outliers, we can see that there is indeed an obvious inverse correlation between wine quality and fixed acidity. This proves that the fixed acidity variable is plays an important role in determining the quality of the wine. It is difficult to see the correlation  if you look at the countplot and displot first before looking at the lineplot, but after seeing the lineplot, a correlation will be quite obvious(This is based on Dylan's EDA, so checkout Dylan's milestone2.ipynb in the analysis folder to see the plots that were mentioned here).

**Ethan**

*Relationship between variables and quality*

From the graphs and the pandas profiling provided above, we can see the correlation of the variables with the quality of the wine. The correlations we see between the variables and the quality did not show strong correlation; however, certain variables show unique graphs. For example, in the graphs between pH vs quality and sulphates vs quality, the quality is almost constant throughout the graph so it will not be a very important variable towards the quality of the wine. Furthermore, we can see some correlation in two graphs that shows a positive and a negative correlation between the variable and the quality of the wine, which are alcohol and fixed acidity, respectively. We can see that those two variables have the greatest effect on the quality of wine so they are the most important variable when trying to change white wine quality. 

From the graph, alcohol shows a stronger correlation since we can see a clearer positive sloped graph, while in fixed acidity, there are certain outliers that are visible but we can still conclude that the graph is negatively sloped. Additionally, in the total sulfur dioxide vs quality graph, we can also see a negative correlation when the amount of sulfur dioxide makes sense (not too little or too much) and even though the graph is similar to fixed acidity where there are certain outliers, we can still see the correlation of each variables through the line plot which is the easiest to see when determining correlation of each variables to the quality. 

Furthermore, in the table where we groupby quality, we can see the correlations that was explained in the paragraphs before from the mean of the values from the variables. Although, the fixed acidity vs quality data did not show a clear positive correlation, the alcohol, which is known to be the most influential variable to the quality, has a clear positive correlation. Also, we can also see a negative correlation in total SO2 vs. quality. Finally, in the violinplot between alcohol and quality, the population of higher quality wine increases as the alcohol percentage increases.

In the plots, the pandas profiling, and the groupby table, we can prove our analysis that as alcohol percentage increases, the quality of the white wine also increases which proves our conclusion that alcohol has a positive correlation with the quality. However, even though we can conclude that there are certain correlation associated between the some variables and the quality of wine, we cannot directly conclude that these variables cause the quality to rise since correlation does not explicitly mean causation. So more research and trial and error would be needed so that the quality of wine can always be improved for customer satisfaction. 

**Conclusion**

In conclusion from our analysis, the variable that affects the quality of white wine the most is the alcohol percentage.