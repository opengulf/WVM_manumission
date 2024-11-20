# Word Vector Models for Gulf History using the India Office Records

This repo contains four word vector models trained using the [WordVectors](https://rdrr.io/github/bmschmidt/wordVectors/man/train_word2vec.html) package in R for File 5 Slave Trade (IOR/R/15/1/199-234) from the India Office Records (IOR). 

The corpus was created in March 2024 using the Text Titan super model in Transkribus. 

| Name of model | n-gram | dimensions | iterations | window | Negative samples | Total training tokens |
| HTR997K1g150d20i6w5ns.bin | 1 | 150 | 20 | 6 | 5 | 914596 |
| HTR997K2g150d20i6w5ns.bin |  2 |  150 | 20  |  6 |  5 | 857994 |  
| HTR997K2g150d20i6w15ns.bin | 2 | 150 | 20 | 6 | 15 | 820391 |
| HTR997K3g150d20i6w5ns.bin | 3 | 150 | 20 | 6 | 5 | 741542 |

Notebooks for querying these models can be found [here](https://github.com/NEU-DSG/wwp-public-code-share/tree/main/WordVectors). 
