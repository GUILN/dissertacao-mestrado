# Paper - 21-03-2024

- [Star Graph Neural Networks for Session-based Recommendation](https://www.semanticscholar.org/paper/Star-Graph-Neural-Networks-for-Session-based-Pan-Cai/63f9bc0d97bdfc80b0227415d170941c211acf43)
- **Tags:** #GNN #session_based_recommendation #outperforms

## Main Information

| Model   | Metric            | Dataset                   | Citations | Date       | Results                                                                               |
| ------- | ----------------- | ------------------------- | --------- | ---------- | ------------------------------------------------------------------------------------- |
| SGNN-HN | #p_at_k #MRR_at_k | #Yoochoose<br>#Diginetica | 118       | 19/10/2020 | Diginetica: P@20 =  4.27 ,MRR@20 = 3.9, <br>Yoochoose:<br>P@20 =  1.11 ,MRR@20 = 2.84 |


## Method

- The proposed SGNN introduces a star node as the transition node between every two items in the session, allowing information propagation not only from adjacent items but also from items without direct connections.
- The use of highway networks helps to solve the overfitting problem and allows for the stacking of more layers of star graph neural networks, leading to better item representation.
- SGNN-HN is effective in hitting the target item in the recommendation list, especially in cases with relatively many candidate items.

**Main Problem that Solves:**
- Outperforms state-of-the-art-models
- Overfitting problems
- Specially in cases when there are many candidates Itens it manages to put with just a few itens in an earlier position so that it enhances the #MRR_at_k metric

## Experiments

- #p_at_k 
- #MRR_at_k 

## Metrics

- #p_at_k 
- #MRR_at_k 


## Results

## Conclusions
- #state-of-art

## Free Notes

The presence of a node that is not part of the itens of the session prevents over-fit and enhances prediction