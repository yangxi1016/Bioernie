BioERNIE: A Pre-trained Biomedical Enhanced Representation through Biomedical Knowledge Integration
The biomedical literature contains a wealth of useful information. This information can be extracted and organized into structured knowledge by natural language processing technology, facilitating the efficient query of biomedical information of interest and providing new insights into the advance bio-related research. Deep learning models have achieved outstanding success in various text mining tasks. However, most of these models focus their sight on dealing with the specific tasks using local and limited data without better untilization of the global and domain-specific knowledge. We explore the application of the recent enhanced representation model ERNIE to biomedical corpora (PubMed abstract and full-text PMC article), and add the information from the two target entities in the Semantic Analysis task to solve the relation extraction task. Besides,We fine-tune BioERNIE and evaluated the popular biomedical text mining tasks (NER, RE）to show the effectiveness of our method. We form a new model named BioERNIE. The performance of BioERNIE is comparable to the previous latest models in two major categories of biomedical text mining tasks (NER and RE). The main improvements include: biomedical named entity recognition in JNLPBA (F1 score increased by 4.23%) and LINNAEUS corpus (F1 score increased by 0.97%) .

ERNIE: https://github.com/PaddlePaddle/ERNIE 

BioERNIE (ERNIE+PubMed) :https://drive.google.com/drive/folders/19v382jHfTklsQoBXwx_fJA3ZPDiBZ0RO?usp=sharing
BioERNIE (ERNIE+PubMed+PMC) :https://drive.google.com/drive/folders/19v382jHfTklsQoBXwx_fJA3ZPDiBZ0RO?usp=sharing

Pre-training data：
PubMed Abstracts1: ftp://ftp.ncbi.nlm.nih.gov/pubmed/baseline/
PubMed Abstracts2: ftp://ftp.ncbi.nlm.nih.gov/pubmed/updatefiles/
PubMed Central Full Texts: ftp://ftp.ncbi.nlm.nih.gov/pub/pmc/oa_bulk/


Test Datasets:
Named Entity Recognition:  8 datasets on biomedical named entity recognition
Relation Extraction:  DDI Corpus

