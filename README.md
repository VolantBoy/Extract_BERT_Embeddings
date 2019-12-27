# Extract_BERT_Embeddings
    Extract character embedding from BERT
# Requirements
    pytorch_transformers
    python3
# Usage
    python extract_features.py \
    --input_file='../statistics/characters.txt' \
    --output_file='./char_emb_768.txt' \
    --character_file='./Characters.txt' \
    --bert_model bert-base-chinese \
    --do_lower_case 
# Paramenters
    input_file:   a file which store character, one character per line 
    output_file:  a file which store character embeddings in word2vec format
    character_file:  a file which store character after tokenizing
