Content and context-driven modeling for sarcasm detection in Reddit Data (SARC dataset).

## Steps

1. Download the [FastText pre-trained embeddings](https://dl.fbaipublicfiles.com/fasttext/vectors-english/crawl-300d-2M.vec.zip) and extract it somewhere.
2. Download the [`comments.json` dataset file](https://drive.google.com/file/d/1ew-85sh2z3fv1yGgIwBoeIHUvP8fMnxU/view?usp=sharing) [1] and place it in `data/`.
3. Download [user_gcca_embeddings.npz](https://drive.google.com/file/d/1mQoe_48LO67plyo98DVeCC9NabVXdm82/view?usp=sharing), place it in `users/user_embeddings/`.
4. cd src
5. python process_data.py [path/to/FastText_embedding]
6. python train_cascade.py
