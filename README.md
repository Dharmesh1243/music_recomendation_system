# music_recomendation_system
The project explores the application of FP-Growth algorithm in association rule mining (ARM) for music recommendation systems using the lastfm dataset. It begins with an introduction to the importance of recommendation systems in music streaming platforms like Spotify and Savan. The methodology involves preprocessing the data using PySpark, exploring the dataset through visualization libraries like Plotly and Seaborn, and applying FP-Growth algorithm for frequent itemset mining. The FP-Growth algorithm's steps are detailed, and three models are developed with different parameter values. Results are presented in terms of association rules and frequent itemsets, showcasing how changing support and confidence thresholds affect the output.

Results:

Three models were developed with different parameter values:

Model 1 with minSupport=0.001 and minConfidence=0.5 produced 273005 frequent itemsets and 171184 association rules.
Model 2 with minSupport=0.01 and minConfidence=0.5 generated 1689 frequent itemsets and 50 association rules.
Model 3 with minSupport=0.1 and minConfidence=0.5 resulted in 7 frequent itemsets and 0 association rules.
Association rules from the models showed varying levels of confidence, lift, and support, indicating the strength of relationships between items.

The paper emphasizes the importance of carefully choosing support and confidence thresholds, noting that low support and high confidence are acceptable rules.

The results suggest that higher lift values indicate stronger associations between items.

Overall, the study demonstrates the efficacy of FP-Growth algorithm in extracting association rules from music listening data, highlighting the significance of parameter selection in generating meaningful recommendations for users.
