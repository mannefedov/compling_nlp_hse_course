## Материалы курса по компьютерной лингвистике (Natural Language Processing course materials)

### Jupyter-ноутбуки курса

#### Вводная часть (1 модуль)
- [**Regexps**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/first_module_intro/01_regular_expressions.ipynb)
- [**Ngrams**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/first_module_intro/02_ngrams.ipynb)
- [**Lexical disambiguation**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/first_module_intro/03_lexical_disambiguation.ipynb)
- [**Language classification**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/first_module_intro/04_textual_corpora.ipynb)
- [**LLM APIs**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/first_module_intro/05_basic_llm_usage.ipynb)

#### Основная часть

1. [**Предобработка текста (Text preprocessing)**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/first_module_intro/01_regular_expressions.ipynb)  
Токенизация, лемматизация, стемминг, pymorphy, mystem, regex, razdel. 
2. [**Классификация текста (мешок слов) (Bag-of-words classification)**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/bow/Bag_of_words_classification.ipynb)  
TFIDF, CountVectorizer, LogReg, KNN, DecisionTrees, Naive Bayes, RandomForest, косинусная близость, тональность текста  
3. [**Поиск и исправление опечаток (Spellchecking)**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/spelling/Spellchecking.ipynb)  
Алгоритм Норвига, расстояние Левенштейна, символьные нграммы, SymSpell. 
4. [**Базовое языковое моделирование (Basic Language Modelling)**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/lm_intro/Language_model_intro.ipynb)  
Вероятность слова, Ngram language model, перплексия, генерация текста. 
5. [**Тематическое моделирование (Topic modelling)**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/topic_modelling/Topic_modelling.ipynb)  
Матричные разложения (SVD, NMF), LDA, перплексия, когерентность. 
6. [**Векторные представления слов (word2vec/fastext) (Word embeddings)**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/word_embeddings/Word_embeddings.ipynb)  
cbow, skip-gram, negative sampling  
7. [**Convolutional Neural Networks for text classification**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/cnn/cnn_keras.ipynb)  
CNN. 
8. [**RNN и извлечение именованных сущностей (Named Entity Recognition)**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/rnn_ner/RNN_NER.ipynb)  
LSTM, GRU, Bidirectional RNN, IOB кодировка, sequence labelling. 
9. **Трансформеры. BERT и GPT (Transformers. BERT and GPT)** ([**BERT**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/transfer_learning_hg/Fine_tunining_pretrained_LMs.ipynb),  [**GPT**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/gpt/gpt.ipynb))  
Transformer, BERT, HuggingFace, fine-tuning, text generation, sampling parameters (temperature, top_p, top_k)  
10. [**Трансформеры. Seq2Seq. Машинный перевод (Transformers. Seq2Seq. Machine Translation)**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/machine_translation/MT_transformer.ipynb)
multi-head attention, encoder-decoder model, bleu score
11. [**Трансформеры. Дообучение на инструкциях (Transformers. Instruct fine-tuning)**](https://github.com/mannefedov/compling_nlp_hse_course/tree/master/notebooks/instruct_fine_tuning)  
alpaca, dolly, flan-t5  
12. [**Трансформеры. PEFT**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/peft/PEFT.ipynb)  
quantization, LoRA, QLoRA  
13. [**Multimodality (text and images)**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/multimodality/CLIP_BLIP_Stable_diffusion.ipynb)  
CLIP, BLIP, Idefics, Stable diffusion   
14. [**Трансформеры. RLHF, DPO**](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/rlhf/RLHF.ipynb)  
human feedback, DPO + QLoRA  





### Архивные jupyter-ноутбуки
- [NER с помощью грамматик (yargy)](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/rnn_ner/NER_rule_based.ipynb)
- [Few-shot NER (deep pavlov)](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/rnn_ner/deep_pavlov_ner.ipynb)
- [Деревья зависимостей (Dependency trees)](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/dependency_parsing/Dependencies_v2.ipynb)
- [Тематическое моделирование в BigARTM](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/topic_modelling/Topic_model_BigARTM.ipynb)
- [Keyword extraction](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/keyword_extraction/Keyword_extraction.ipynb)
- [CNN (tf)](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/cnn/cnn_tf.ipynb), [CNN (pytorch)](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/cnn/cnn_torch.ipynb)
- [RNN (pytorch)](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/rnn_ner/rnn_torch.ipynb)
- [Deep learning intro (tf)](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/word_embeddings/nn_intro_tf.ipynb), [Deep learning intro (pytorch)](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/word_embeddings/nn_intro_torch.ipynb)
- [Кластеризация (Clustering)](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/wsd/clustering_tutorial.ipynb)
- [Морфологическая дизамбигуация](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/morphology/%D0%9C%D0%BE%D1%80%D1%84%D0%BE%D0%BB%D0%BE%D0%B3%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F%20%D0%B4%D0%B8%D0%B7%D0%B0%D0%BC%D0%B1%D0%B8%D0%B3%D1%83%D0%B0%D1%86%D0%B8%D1%8F.ipynb)
- [Использование предобученных моделей (pytorch)](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/transfer_learning_hg/Fine_tune_pretrained_LM_torch.ipynb)
- [Viterbi/MEMM](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/other/MEMM_viterbi.ipynb)
- [Sentence tokenization](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/other/Sentence_tokenizer.ipynb)
- [Relation extraction](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/other/Relation_extraction.ipynb)
- [Semantic Role Labelling](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/notebooks/other/srl.ipynb)


### Jupyter-notebooks in English
- [Text preprocessing](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/english_notebooks/Preprocessing_Eng.ipynb)
- [Basic Language modelling](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/english_notebooks/Ngrams-Eng.ipynb)
- [Topic modelling](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/english_notebooks/Topic_model_gensim_sklearn_eng.ipynb)
- [Word Embeddings](https://github.com/mannefedov/compling_nlp_hse_course/blob/master/english_notebooks/Embeddings.ipynb)

