# *Detectando Emails Phishing com Machine Learning* 

Os dados foram obtidos pela plataforma [Kaggle](https://www.kaggle.com/datasets/ethancratchley/email-phishing-dataset).

Este conjunto de dados contém informações sobre emails para serem utilizados na detecção de possíveis phishings.

A partir dessas informações, é possível treinar um algoritmo para identificar se um email pode ser ou não um phishing.


Objetivo: **Classificação (predição) se um email é phishing ou não**



**Dicionário de dados:**

| Variável                | Descrição                                                             |
|------------------------|-------------------------------------------------------------------------|
| num_words              | Número total de palavras no corpo do e-mail                             |
| num_unique_words       | Contagem de palavras únicas utilizadas                                  |
| num_stopwords          | Contagem de palavras comuns (por exemplo, "o", "e", "em")               |
| num_links              | Número de links detectados                                              |
| num_unique_domains     | Número de domínios únicos nos links (por exemplo, "paypal.com")         |
| num_email_addresses    | Contagem de endereços de e-mail encontrados no texto                    |
| num_spelling_errors    | Contagem de palavras com erros ortográficos                             |
| num_urgent_keywords    | Número de palavras de urgência (por exemplo, "urgente", "verificar")    |
| label                  | Variável alvo: 0 = E-mail seguro, 1 = E-mail de phishing                 |



