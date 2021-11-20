# Desafio Hadoop e GCP - DIO.me

Resultado do desafio Hadoop e GCP da plataforma [DIO](https://www.dio.me/en).

Foi executado, em um cluster criado no GCP, o arquivo 'contador.py', que realizou a contagem da aparição de cada palavra em um outro arquivo, 'livro.txt'. Ambos os arquivos podem ser conferidos na pasta 'job_files'.

O cluster criado recebeu o nome de '**cluster-dio-hadoop**' e o bucket foi nomeado '**diomedataproc**'.

O resultado total obtido pode ser encontrado no arquivo 'resultado_part-00000', e as 10 palavras com mais aparições podem ser conferidas no arquivo 'resultado.txt'.

### Spoiler - Resultado

Adiantando, as 10 palavras com maior contagem de aparição, desconsiderando o resultado vazio ('') e as vogais soltas 'I' e 'a', são:

* THE = 4066 vezes
* AND = 2969 vezes
* OF = 2746 vezes
* TO = 2144 vezes
* MY = 1631 vezes
* IN = 1129 vezes
* WAS = 994 vezes
* THAT = 986 vezes
* WITH = 700 vezes
* HAD = 679 vezes