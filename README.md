# Projeto dataproc
### Criando um ecossistema hadoop totalmente gerenciado com google cloud dataproc

## - Etapas do Desafio
* Criar um bucket no Cloud Storage
* Atualizar o arquivo contador.py com o nome do Bucket criado nas linhas que contém {SEU_BUCKET}.
* Fazer o upload dos arquivos contador.py e livro.txt para o bucket criado 
* Utilizar o código em um cluster Dataproc, executando um Job do tipo PySpark chamando gs://{SEU_BUCKET}/contador.py

O Job irá gerar uma pasta no bucket chamada resultado. Dentro dessa pasta o arquivo part-00000 irá conter a lista de palavras e quantas vezes ela é repetida em todo o livro.
#### - entrega do resultado do desafio

* Criar um repositório no GitHub.
* Criar um arquivo chamado resultado.txt. Dentro desse arquivo, colocar as 10 palavras que mais são usadas no livro, de acordo com o resultado do Job.
* Inserir os arquivo resultado.txt e part-00000 no repositório e informar na plataforma da Digital Innovation One.

O desafio faz parte do Bootcamp Banco Carrefour Data Engineer na plataforma de educação Digital Innovation One.
