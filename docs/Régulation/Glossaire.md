 !! Les modifications de Raphaël !!
((( les modifications de beatrice)))
**Voici**le vocabulaire [^1] à connaître +++ pour décrypter le domaine. Il est classé par thématiques. Ce classement, totalement arbitraire, 
Entité nommé (NER)

---------- 

Embedding

## Machine learning 
### Paramètres : 
> Les paramètres d'un **modèle** designent les variables qui sont apprises par le modèle lors de la
> >> phase d'apprentissage. 
### Hyperparamètres : 
On destingue les hyperparamètres du modèle (nombre de couches, taille, ... ) et ceux liés à l'apprentissage (learning rate, optimizer, ... ). 

Transfert d'apprentissage
L’apprentissage par transfert peut être vu comme la capacité d’un système à reconnaître et à appliquer des connaissances et des compétences, apprises à partir de tâches antérieures, sur de nouvelles tâches ou domaines partageant des similitudes


Dépendances (dependencies)

Part Of Speech

Stopwords 

NLP 

Prompting

GPT (Generative Pre-trained Transformer)

Tokenizer 

Transformer 

Attention

Self Attention 



Sparse matrice 
Bag of words 
Dense vectors
Fine tuning 


RAG 
in_context learning
zero shot learning
few shots learning

Precision
Recall 
F1 score
Perplexité 

RNN
LSTM
GRU
Logits

Standard Q&A
Open Q&A
Generative Q&A

TF-IDF

BM25

Jacard (distance)

Normalisation

Token

BPE

UTF

Ontologie 
Knowledge graph

## Transformers

### Les notions clés 
#### Attention 
#### Encoder
#### Decoder 



### Les architectures 

####  Encoders or autoencoding models
As mentioned before, these models rely on the encoder part of the original transformer and use no mask so the model can look at all the tokens in the attention heads. For pretraining, targets are the original sentences and inputs are their corrupted versions.
Exemples : BERT, CamemBERT, FlauBERT, JuriBERT

#### Decoders : Autoregressive Model (AR) for Language Modelling : 
modèle qui prédit les valeurs futures à partir de valeurs passées. GPT fait partie de ce type de modèle. 
Exemples : GPT J, BLOOM,  GPT (openAI)
Cedille : https://arxiv.org/abs/2202.03371 
GPT (openAI) : 
Codex (openAI) : 
OPT(Meta) : 
PALM (Google): à creuser
BLOOM (Huggingface) : 
GPT-NeoX (Eleuther AI) : 
GPT-J

#### Encoder - Decoder : Sequence-to-sequence models
As mentioned before, these models keep both the encoder and the decoder of the original transformer.
Exemple : T5

#### Sentence Transformer




Transformers
Encoder
Decoder 
Attention

Librairies logicielles spécialisées dans la recherche d'informations : 
Elasticsearch
Faiss
Qdrant
Pinecone

Services en ligne de NLP : 
Voici une liste des services proposant, via des api, l'utilisation de modèles déjà hébergés. J'ai volontairement écarté les solutions de cloud des géants du secteur (Azur, Google, Amazon). 








Liste non exhaustive des LLM : 





Similarité cosinus 

Distance euclidienne

BERT 

Encoder 

Decoder

Dataset (jeu de données) : ensemble de données, structurées ou non, utilisée par des algorithmes d'apprentissage machine. 

Données structurées : données ayant été formatées en vue d'un traitement algorithmique spécifique. Par exemple, les jeux de données permettant d'identifier des entités dans un texte comme des références légales. 
Données non structurée : données non formatées en vue d'une exploitation directe par un algorithme. Il peut s'agir de documents comme des pdf, emails, images. 

Legal NLP


[^1] : footnote


