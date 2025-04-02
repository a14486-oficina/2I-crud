# 2I-CRUD
Este é um projeto simples desenolvivdo em ambiente escolar. Neste projeto criei uma página web, com o sistema CRUD, com o objetivo de simular a visão de um admin que gere um menu online.

# Funções
Neste projeto é possível
As funções no meu projeto são:
  1. Criar um produto
  2. Editar um produto
  3. Remover um produto

# Requesitos
  1. **Base de dados** - phpMyAdmin
  2. **Alojamento Web** - Alojamento Grátis
# Estrutura de Fichieros
```bash
├── /css/                     # Pasta que guarda o ficheiro .css
      ├── style.css           # Ficheiro .css (estilo da página web)
├── /db/                      # Pasta que guarda o ficheiro .sql 
      ├── cart_db.sql         # Ficheiro .sql (base de dados)
├── /images/                  # Pasta que guarda as imagens que podem ser usadas na página web(opcional)
      ├── food-1.png          # Ficheiro da foto
      ├── food-2.png          # Ficheiro da foto
      ├── food-3.png          # Ficheiro da foto
      ├── food-4.png          # Ficheiro da foto
      ├── food-5.png          # Ficheiro da foto
├── /uploaded_img/            # Pasta que guarda as imagens que forem enviadas para a base de dados
├── admin_page.php            # Ficheiro principal
├── admin_update.php          # Ficheiro para dar update de um produto
└── config.php                # Ficheiro para conectar à base de dados
```
# Como implementar

  1. Aceder ao [Alojamento Grátis](http://www.alojamento-gratis.com/?i=1).
  2. Clicar em "alojamento web grátis", na navbar no topo da página. <b>Observação</b>: Se tiveres conta criada podes <b>saltar para o passo 6.1.</b>
  <img src="https://drive.google.com/uc?export=view&id=1DDQZxnMBm5BMopwWacAh_gkH45UYIBxu" alt="Alojamento Web grátis" width="500">
  3. Descer a página até aparecer o botão "Peça já o seu alojamento web grátis" e clicar no botão.
  <img src="https://drive.google.com/uc?export=view&id=1ZGt2M5eORxPp5ZuJY_URnTff6OlZ6U3v" alt="Peça já o seu alojamento grátis" width="500">
  4. Preencher os dados do resgisto e clicar no botão para continuar. <br>
  5. Ir ao email, e clicar no link da nossa página web. <b>Obserevação</b>: o email pode estar no spam. <br>
  6. Clicar no link que corresponde ao CPanel e deve colocar o username respetivo ao CPanel e a palavra-passe que defeniu. <br>
    6.1 <b>Este passo só se aplica se você já tem conta criada</b> - Clicar em "Login" na navbar e deve colocar o username respetivo ao CPanel e a palavra-passe que defeniu. <br>
  7. Clicar no botão "I approve". <b>Observação</b>: Faça este passo caso seja a primeira <b>pode saltar este passo</b><br>
  8. Clicar em "Online File Maneger" <br>
  9. Ciar uma nova pasta ou usar a pasta htdocs e colocar os ficheiros, exeto o ficheiro da base de dados. <br>
  10. Voltar ao CPanel e clicar em "MySQL Databases". <br>
  11. Dar um nome a base de dados e clicar no botão "Create Database". <br>
  12. Clicar no botão admin, respetivo a base de dados criada, na tabela em baixo. <br>
  13. Clicar em "Importar", na navbar. <br>
  14. Clicar no botão "Escolher ficheiro" e selecionar o ficheiro .sql, que foi disponibilizado. <br>
  15. Voltar ao menu "MySQL Database", para verificar os dados de acesso da base de dados.
  16. Ir ao "Online File Maneger", ir a pasta em que colocou os ficheiros e abrir o ficheiro config.php e colocar os dados de acesso a base de dados. <b>Observação</b>: No MySQL Database, o primeiro campo representa o último campo do ficheiro config.php, o último campo do MySQL representa o primeiro campo do ficheiro.php e os dois campos do meio mantêm-se igual, por fim deve <b>salvar o ficheiro</b> config.php. <br>
  17. Para acabar deves aceder a página web, o link está no email enviado, ao criar a conta. <b>Observação</b>: Tem que colocar, depois do fim do link, o seguinte complemento "/nome da pasta/nome do ficheiro(neste caso "admin_page.php")" <br>

  
  
