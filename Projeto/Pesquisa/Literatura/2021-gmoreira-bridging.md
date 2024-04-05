# 2021-gmoreira-bridging

- [Transformers4Rec: Bridging the Gap between NLP and Sequential / Session-Based Recommendation](https://www.semanticscholar.org/paper/Transformers4Rec%3A-Bridging-the-Gap-between-NLP-and-Moreira-Rabhi/dca4d9abbc82e57dfa52f932e893d467a63e0682)
- **Tags:** #GNN #transformers
- **Published At:** [[ACM Conference Series On Recommendation Systems]]

## Main Information

| Model        | Metric                | Dataset                                  | Citations | Date       | Results                                     |
| ------------ | --------------------- | ---------------------------------------- | --------- | ---------- | ------------------------------------------- |
| #BERT #XLNet | #ndcg_at_k<br>#p_at_k | [[Sigir]], [[Booking]],<br>[[Yoochoose]] | 98        | 13-09-2021 | YOOCHOOSE (P@20 = 0.6384, NDCG@20 = 0.3776) |


## Method

**Description:**
- The paper does a overall review of #transformers  applicability to recommendation domain
- The paper introduces the library: #transformers4rec that bridges the gap between #transformers usage for recommendation and NLP, research area which the author affirms that is way more advanced in #transformers applicability than recommendation
- The paper also performs an comparison among the application of different #transformers architecture for recommendation tasks, with different training approaches
- Shows that the inclusion of side information uniformly improves the recommendation
- The library presented in this work is a implementation of the #hugging_face_transformer architecture

**The paper investigates the following questions:**
- RQ1: Can transformer-based architectures provide accurate next-click predictions for the usually short user sequences found in the session-based recommendation task? 
- RQ2: How do the training techniques of CLM, MLM, PLM, and RTD comparatively perform for the task of session-based recommendation? 
- RQ3: What are effective approaches to integrate additional features, commonly referred to as side information, into transformer architectures in order to improve recommendation performance?
## Experiments

## Metrics

## Results

## Conclusions

## Free Notes
