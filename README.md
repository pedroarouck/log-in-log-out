# Login/Logout

Projeto baseado no desafio:

>Neste desafio o candidato terá total liberdade de usar as ferramentas e linguagens que está mais familiarizado. O objetivo principal será identificar sua criatividade e a capacidade de resolver um problema, principalmente o potencial de implementação, qualidade de código, organização, boas práticas, conceitos de Clean Code, SOLID e preocupação com desenvolvimento para grandes volumes transacionais. Você é responsável por desenvolver a solução, definir o modelo de entrega, utilizando-se das ferramentas de mercado atuais, bem como por pensar em compartilhamento de código, versão de fontes etc. O desafio consiste em criar uma solução para atender um requisito de um projeto: Nosso cliente fictício será a empresa Oliveira Trade e foi solicitado pelo board da empresa que seja desenvolvido uma forma de Sign in e Sign up de usuários. Devemos permitir que seja criado um usuário no sistema, com os campos mínimos de cadastro normal para Pessoa Física. O usuário deve ser notificado que o cadastro foi concluído com sucesso e, a partir deste ponto, ser possível executar login. NÃO É MANDATÓRIO o desenvolvimento de uma interface front end, já que o board aceita como entrega - um serviço que possa ser consumido e executar as atividades requisitadas, desde que o desenvolvedor crie uma boa entrega com o manual de como utilizar o serviço. CONSIDERAÇÕES FINAIS: esperamos que consiga executar até o final, entretanto, mesmo que não consiga concluir totalmente, pedimos que entregue o que conseguir.

## Ferramentas Utilizadas

- [Python](https://www.python.org/downloads/)
- [Django](https://www.djangoproject.com/download/)
- [TinyMCE](http://romanvm.github.io/django-tinymce4-lite/configuration.html)
- [Materialize](https://materializecss.com/)

## Inicializando

Para inicializar localmente o servidor, digite o comando *runserver* no console.
```
$ ...\log-in-log-out-master>python manage.py runserver
```
É possível verificar o funcionamento do servidor no endereço http://127.0.0.1:8000
Para criar um super usuário, é preciso inserir o comando *createsuperuser* no console.

```
$ ...\log-in-log-out-master>python manage.py createsuperuser

  Username (leave blank to use 'localname'): 
  Email address: 
  Password:
  Password (again):
  Superuser created successfully.

```
**Já está criado o super usuário admin, com senha admin.**

### Agradecimento especial

- Sentdex, de [Python Programming tutorials](https://pythonprogramming.net/)
