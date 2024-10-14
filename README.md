# Facilitating Interdisciplinary Knowledge Transfer with Research Paper Recommendation

Replication data available at: https://doi.org/10.7910/DVN/P62Q5V

COMBSAGE code available at: https://github.com/eoghancunn/combsage

The basic workflow is: 
1. Fit embeddings for papers published up to 2016 (citation_networks/2016.gexf). e.g: **021_ComBSAGE.ipynb**
2. Train a recommender to recommend papers that will be co-cited with a sample of query papers from 2016 (co_citations/2016.json). **022_train_recommender.ipynb**
3. Infer emebeddings for all papers published up to 2017 (citation_networks/2017.gexf) 
4. Generate recommendations for all papers published in 2017. **023_generate_recommendations.ipynb**
5. Evaluate relevance using co-citations as ground-truth. **031_evaluate_relevance.ipynb**
6. Evaluate recommendation novelty and diversity using network distance and semantic distances.  **032_evaluate_novelty_diversity.ipynb**

