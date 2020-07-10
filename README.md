# Movie recommender
Recommends movies based on user ratings. Uses Embarrassingly Shallow AutoEncoders for Sparse Data.

# Notes
* The code in `model.py` file is the propriety of [Darel13712](https://github.com/Darel13712/ease_rec).

### Input
Pandas DataFrame with columns: [`user_id`, `item_id`, [`rating`]] for both fit and predict.

### Output
Pandas DataFrame with columns: [`user_id`, `item_id`, `score`].

# References
* [Steck, Harald. "Embarrassingly Shallow Autoencoders for Sparse Data." The World Wide Web Conference on - WWW '19 (2019): n. pag. Crossref. Web.](https://arxiv.org/pdf/1905.03375v1.pdf)
* [EASE code (GitHub Repository)](https://github.com/Darel13712/ease_rec)