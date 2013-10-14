django-test
===========

Projeto de teste para candidatos.

Descrição
---------
Este é um projeto utilizado para testar as habilidades de desenvolvimento e aprendizado dos candidatos a vaga de desenvolvedor python júnior.

O objetivo principal é modificar uma aplicação django simples para cadastrar um conjunto de dados simples e recuperlá-los posteriormente. Um conjunto de tarefas extras está disponível para melhorar a pontuação no teste, mas não são obrigatórias para o envio.

Preparativos para desenvolvimento
---------------------------------
Requisitos:
* python 2.7
* mysql
* python-virtual-env
* pip

Instruções:
* Com os softwares acima instalados, executar o script bootstrap.sh
* Instalar dependencias: pip install -r requirements.txt
* Rodar servidor: (python manage.py runserver)
* Testar se está no ar abrindo um navegador no endereço localhost:8000/static/running.html


Tarefa principal
----------------
Criar uma função que recebe uma requisição HTTP que recebe os dados do formulário presente no arquivo estático django-test.html e grave em um banco de dados. (URL: /django-test/send_data)

Dados do banco:
* HOST: localhost
* DATABASE: banco-[usuario-github]
* USER: usuario-[usuario-github]
* PASSWORD: django-test


Tarefas extras
--------------
* Converter a função principal criada para aceitar apenas requisições POST
* Criar uma função GET que retorna os dados cadastrados em formato JSON (URL: /django-test/get_data)
* Renderizar a resposta da função GET em um template.



Entrega
-------
Para a entrega, o candidato deve fazer um fork deste repositório, realizar todo o desenvolvimento em seu fork e fazer um pull request. Incluir nome e email no pull request para identificação do candidato.

