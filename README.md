# desafio_dataproc
Criando um Ecossistema Hadoop Totalmente Gerenciado com Google Cloud Dataproc

Desafio GCP Dataproc
Criando um ecossistema Hadoop totalmente gerenciado com Google Cloud Platform

O desafio consiste em efetuar um processamento de dados utilizando o produto Dataproc do GCP. Esse processamento irá efetuar a contagem das palavras de um livro ("Frankenstein or, The Modern Prometheus") e informar quantas vezes cada palavra aparece no mesmo.

Etapas do Desafio
Criar um bucket no Cloud Storage

Atualizar o arquivo contador.py com o nome do Bucket criado nas linhas que contém {SEU_BUCKET}.

Fazer o upload dos arquivos contador.py e livro.txt para o bucket criado (instruções abaixo)

https://cloud.google.com/storage/docs/uploading-objects
Utilizar o código em um cluster Dataproc, executando um Job do tipo PySpark chamando gs://{SEU_BUCKET}/contador.py

O Job irá gerar uma pasta no bucket chamada resultado. Dentro dessa pasta o arquivo part-00000 irá conter a lista de palavras e quantas vezes ela é repetida em todo o livro.

Entrega do Resultado
Criar um repositório no GitHub.
Criar um arquivo chamado resultado.txt. Dentro desse arquivo, colocar as 10 palavras que mais são usadas no livro, de acordo com o resultado do Job.
Inserir os arquivo resultado.txt e part-00000 no repositório e informar na plataforma da Digital Innovation One.
Considerações Finais
NOTA: Se o Job mostrar um WARN de Interrupt, basta ignorar. Existe um bug no Hadoop que é conhecido. Isso não impacta no processamento.

Qualquer outra dúvida, informação ou sugestão, fique a vontade para entrar em contato.
