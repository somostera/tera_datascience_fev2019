# Aula #30 – Análise de Tópicos & Sistemas de recomendação

## Dataset utilizado

O dataset utilizado é uma versão reduzida do dataset de [goodbooks-10k](https://github.com/zygmuntz/goodbooks-10k).

Baixe o dataset e o coloque na pasta `resources/data`: 

* opção 1: no terminal, de dentro da pasta desta aula, rode o comando: 

    ```bash
    git clone -b only-reduced --single-branch https://github.com/cimarieta/goodbooks-10k.git resources/data/
    ```

* opção 2: caso queira fazer isso manualmente, faça download de todos arquivos que estão no [repositório](https://github.com/cimarieta/goodbooks-10k/tree/only-reduced/reduced) e os coloque na pasta `resources/data/reduced` (caminho relativo à pasta referente a esta aula).


## Pré-aula - obrigatório

* conceitos de álgebra linear:
    * [introdução sobre vetores](https://www.youtube.com/watch?v=fNk_zzaMoSs)
    * [sobre combinações lineares, subespaços e bases](https://www.youtube.com/watch?v=k7RM-ot2NWY)

* aulas 3 e 4 Unsupervised Learning in Python [DataCamp](https://www.datacamp.com/courses/unsupervised-learning-in-python)

### Opcionais, mas legais :)

* sobre o algoritmo que venceu a competição do _Netflix_ no Kaggle:
[link](https://datajobs.com/data-science-repo/Recommender-Systems-[Netflix].pdf)

* sobre a competição do _Netflix_ no Kaggle e por que o algoritmo vencedor não foi implementado:
[link](https://medium.com/netflix-techblog/netflix-recommendations-beyond-the-5-stars-part-1-55838468f429)

* sobre a evolução do sistema de recomendação do _New York Times_ (até 2015):
[link](https://open.blogs.nytimes.com/2015/08/11/building-the-next-new-york-times-recommendation-engine/)

* sobre a mudança no comportamento do sistema de recomendação do _YouTube_ (jan/2019):
[link](https://www.theverge.com/2019/1/25/18197301/youtube-algorithm-conspiracy-theories-misinformation)

* sobre a ideia por trás dos modelos de recomendação que envolvem fatores latentes (e.g. SVD):
[link](https://www.youtube.com/watch?v=E8aMcwmqsTg&list=PLLssT5z_DsK9JDLcT8T62VtzwyW9LNepV&index=55)

* sobre redução de dimensionalidade
[link](https://www.youtube.com/watch?v=jPmV3j1dAv4)

* sobre pensar em dimensões maiores:
[link](https://www.youtube.com/watch?v=zwAD6dRSVyI)

### Livros

* [Practical Recommender Systems (Kim Falk)](https://www.manning.com/books/practical-recommender-systems)
Livro bastante prático e que cobre o básico de sistemas de recomendação. Contém trechos de código com implementação em Python.

* [Mining of Massive Datasets (Jure Leskovec, Anand Rajaraman, Jeff Ullman)](http://www.mmds.org/)
Apesar de não ser um livro específico sobre sistemas de recomendação, traz vários das técnicas utilizadas para gerar recomendações. Contém boas explicações teóricas e está disponível online.
