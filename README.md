# Blog Ruby on Rails

## Contextualização
O blog foi criado para um teste técnico realizado pela empresa ATM, utilizando banco de dados e Ruby on Rails. Este é meu primeiro projeto em Ruby, e confesso que foi um pouco complicado de efetuar.

## Referências
- [Como INSTALAR e CONFIGURAR o MYSQL - O Guia Completo](https://www.youtube.com/watch?v=oi3UHWXLxLs&t=456s)
- [CRIANDO UM BLOG COM RUBY ON RAILS](https://www.youtube.com/watch?v=tafq9Zfdgpk&t=348s)
- [Construindo uma aplicação Ruby On Rails em 3 minutos](https://www.youtube.com/watch?v=ZGSQ4elUJG8)
- [Build a Blog with Rails Part 1: Rails New](https://www.youtube.com/watch?v=i2rTiEhQzig)
 
Também utilizei IA's para me auxiliarem durante o desenvolvimento, tanto ChatGPT quanto DeepSeek.

## Banco de Dados
**PostgreSQL**

**Obs:** (Sei que no projeto foi solicitado o uso do MySQL, porém, durante o desenvolvimento e nos tutoriais, enfrentei problemas com a versão das gems e do MySQL. Não consegui encontrar a solução, mesmo ajustando as versões do Ruby, Rails e MySQL. Após recorrer a IA's e várias tentativas sem sucesso, optei por utilizar o PostgreSQL, pois foi a tecnologia com a qual tive mais experiência durante os semestres da faculdade, ao contrário do MySQL, que nunca utilizei antes.)

## Personalizações
- Não há personalizações além da estrutura básica dos tutoriais. Tentei integrar o Bootstrap e instalei as gems necessárias, mas ao rodar o servidor, outros problemas surgiram e não foram possíveis de resolver conforme desejado.

## Como Rodar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/Aryzada/blogATM

2. Navegue até o diretório do projeto:
    cd blog

3. Instale as dependências 
    bundle install

4. Crie o banco e as tabelas
rails db:create
    rails db:migrate 

5. Inicie o servidor
    rails server  
