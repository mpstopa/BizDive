# BizDive
This repo contains python code for webscraping pages of companies (or other webpages) from a supplied
list of URLs. It then takes the scraped text and formats it for a second code which performs doc2vec
from gensim to cluster those websites based on their content. The doc2vec employs t-SNE in 3D to
visualize the clustering results.
