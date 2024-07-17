# Gerador de Respostas para Requerentes Frequentes <p>
Repositório do desenvolvimento de um gerador de respostas para requerentes frequentes da Ouvidoria do Serviço Exterior. <p><p>

# Ferramentas e bibliotecas necessárias<p>
1 Python. Linguagem de programação principal, disponível em https://www.python.org/. <p>
2 NLTK. Biblioteca em Python, disponível em https://www.nltk.org/. Será usada para analisar os textos das manifestações e armazenar os dados relevantes (ocorrência de palavras e outros). <p>
3 PostgreSQL. Sistema gerenciador de banco de dados, disponível em https://www.postgresql.org/. Armazenará tanto as manifestações dos requerentes quanto as respostas para tais manifestações. <p>
4 Git. Sistema de controle de versão de código fonte, disponível em https://git-scm.com/downloads. Para manter o código atualizado, seguro e adaptável. <p>
5 Flask . Microframework web em Python, disponível em https://flask.palletsprojects.com/en/3.0.x/installation/#python-version. Seu uso será a criação da aplicação web. <p>
6 HTML/CSS/JavaScript. Linguagem de marcação de texto, estilo e programação web para design de UI. <p>
7 Plataforma de hospedagem para que o site esteja no ar. <p>
8 spaCy. Biblioteca Python para processamento de Linguagem Natural, disponível em https://spacy.io/.
<p>
  
# Passo a passo esperado do desenvolvimento: <p>
1 Coleta e armazenamento de dados. Criação de um banco de dados com as manifestações dos requerentes frequentes; <p>
2 Análise do conteúdo dessas manifestações. Extração de palavras e frases frequentes para a criação de F.A.Q; <p>
3 Implementação do algoritmo de resposta. Código para identificar se i. a pergunta é repetida; ii. a manifestação não é duplicada; iii. sugerir resposta manual se a pergunta for inédita; iv. sugerir arquivamento se houver mensagem inadequada; <p>
4 Desenvolvimento web. Desenvolvimento do site com usabilidade simplificada e interface amigável e intuitiva. Implementação da lógica no Flask; <p>
5 Deploy do site. Colocar o site no ar usando plataformas de hospedagem. <p>

