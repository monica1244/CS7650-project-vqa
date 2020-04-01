# CS7650-project-vqa
#### Images (~745 MB): Training (5k), Validation (1k)
https://drive.google.com/file/d/1cLUCEGM4UW_GrI5iZdZfdLaPjM0hYvx_/view

Get combined_train_input.npy from https://drive.google.com/open?id=1_PkcsLndQb42SvwXRTU6SK-9_TvoKfVh and paste it in the preprocessed_data folder

Get train_image_list.npy from https://drive.google.com/open?id=12zyK8Joa8F0CtpwVWW4alcY7cK-q22h9

Get val_image_list.npy from https://drive.google.com/open?id=16L8NwE7S48Q2LyPtWqwU8L0Tv8KZCdRw

<br><br>
#### Pre-processed data:
###### train_dataset_5k.json: Contains 5k randomly chosen question, answer, image triplets from the training dataset.
###### val_dataset_1k.json: Contains 1k randomly chosen question, answer, image triplets from the validation dataset.

###### answer_tokens_top1k.json: Contains the Top 1k answers (sorted by frequency) from the training dataset in tokenised form.
###### train_dataset_5k_tokenised.json: Contains most common answer (amongst 10 answers for each question with count >= 3) in tokenised form using tokenisation dictionary from answer_tokens_top1k.json
###### val_dataset_1k_tokenised.json: Contains most common answer (amongst 10 answers for each question with count >= 3) in tokenised form using tokenisation dictionary from answer_tokens_top1k.json
