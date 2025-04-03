# 📌 2I-CRUD
Este é um projeto simples desenolvivdo em ambiente escolar. Neste projeto criei uma página web, com o sistema CRUD, com o objetivo de simular a visão de um admin que gere um menu online.

# 🛠️ Funções
As funções deste projeto são:
  1. Criar um produto
  2. Editar um produto
  3. Remover um produto
  4. Ler um produto existente

# 🚀 Requesitos
  1. **Base de dados** - phpMyAdmin
  2. **Alojamento Web** - Alojamento Grátis
     
# 📂 Estrutura de Fichieros
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
# ⚙️ Como implementar

  1. Aceder ao [Alojamento Grátis](http://www.alojamento-gratis.com/?i=1).
  2. Clicar em "alojamento web grátis", na navbar no topo da página. <b>Observação</b>: Se tiveres conta criada podes <b>saltar para o passo 6.2.</b>
  <br>
  <img src="https://drive.google.com/uc?export=view&id=1DDQZxnMBm5BMopwWacAh_gkH45UYIBxu" alt="Alojamento Web grátis" width="500">
  3. Descer a página até aparecer o botão "Peça já o seu alojamento web grátis" e clicar no botão. <br>
  <br>
  <img src="https://drive.google.com/uc?export=view&id=1ZGt2M5eORxPp5ZuJY_URnTff6OlZ6U3v" alt="Peça já o seu alojamento grátis" width="500">
  4. Preencher os dados do resgisto e clicar no botão para continuar. <br>
  <br>
  <img src="https://drive.google.com/uc?export=view&id=1iB9GwaRlMX6MFJM3_ddsPnYP0e-di2gm" alt="Formulário" width="500">
  5. Ir ao email, e clicar no link da nossa página web. <b>Obserevação</b>: o email pode estar no spam. <br>
  <br>
  <img src="https://drive.google.com/uc?export=view&id=155rerKVtiixYO0ntPBlRbXRPPPCNSxij" alt="Link no email" width="500">
  6. Clicar no link que corresponde ao CPanel e deve colocar o username respetivo ao CPanel e a palavra-passe que defeniu. <br>
  <br>
  <img src="https://drive.google.com/uc?export=view&id=1iKf33ijzhh6RxeoHCv63afD-HRywMTFx" alt="Link correspondente ao CPanel" width="500">
  <img src="https://drive.google.com/uc?export=view&id=1o_kgsagXV5g6RdIcvmMI2o-XssbUIY2X" alt="Login no CPanel" width="500">
     6.1. Clicar no botão "I approve". <b>Observação</b>: Faça este passo caso seja a primeira <b>pode saltar este passo</b><br>
  <br>
  <img src="https://drive.google.com/uc?export=view&id=13t2Y2zxVwI4N_sbAmqLB7BLdCnjp0Ksd" alt="Clicar em I Approve" width="500">
    6.2 <b>Este passo só se aplica se você já tem conta criada</b> - Clicar em "Login" na navbar e deve colocar o username respetivo ao CPanel e a palavra-passe que defeniu. <br>
    <br>
    <img src="https://drive.google.com/uc?export=view&id=1zQY0E8bSOhtrkl-CnKvqlGz7OZ0qC0Q4" alt="Login no Alojamento grátis" width="500">
    <img src="https://drive.google.com/uc?export=view&id=1o_kgsagXV5g6RdIcvmMI2o-XssbUIY2X" alt="Login no CPanel" width="500">
  7. Clicar em "Online File Maneger" <br>
  <br>
  <img src="https://drive.google.com/uc?export=view&id=1rffW5CIUvqPRgqxtTnCzV1hokIRsSa8Y" alt="Clicar em Online File Maneger" width="500">
  8. Criar uma nova pasta dentro da htdocs ou usar a pasta htdocs para colocar os ficheiros, exeto o ficheiro da base de dados. <br>
  <br>
  <img src="https://drive.google.com/uc?export=view&id=1v3KWnfVBwvWFXw_6ZcPDvVrktRCllOYW" alt="Pasta com os ficheiros" width="500">
  9. Voltar ao CPanel e clicar em "MySQL Databases". <br>
  <br>
  <img src="https://drive.google.com/uc?export=view&id=1VLeIX5f3RTCRQedCHipZYo0yEbvuXNQx" alt="Clicar em MySQL" width="500">
  10. Dar um nome a base de dados e clicar no botão "Create Database". <br>
  <br>
  <img src="https://drive.google.com/uc?export=view&id=1jTvg5Q8bYA4Rl_-xPnJI_KM0LfOq4sGq" alt="Criar base de dados" width="500">
  11. Clicar no botão admin, respetivo a base de dados criada, na tabela em baixo. <br>
  <br>
  <img src="https://drive.google.com/uc?export=view&id=1JZ_EOcIt9TZoKBEwL8ecE0Tm3SfFGEDm" alt="Clicar e admin" width="500">
  12. Clicar em "Importar", na navbar. <br>
  <br>
  <img src="https://drive.google.com/uc?export=view&id=1t9UkkssbLP4DfAWlQpPjx5FrAlseiZr8" alt="Clicar em importar" width="500">
  13. Clicar no botão "Escolher ficheiro" e selecionar o ficheiro .sql, que foi disponibilizado. <br>
  <br>
  <img src="https://drive.google.com/uc?export=view&id=1Ft7focfXe-zpuaiUbxr7BnNKS_28Swpt" alt="Ficherio selecionado" width="500">
  14. Voltar ao menu "MySQL Database", para verificar os dados de acesso da base de dados.
  <br>
  <img src="https://drive.google.com/uc?export=view&id=1iwMVL6p_3w4t2shvujd6AIkQSZ-_QyXp" alt="Verificar os dados" width="500">
  15. Ir ao "Online File Maneger", ir a pasta em que colocou os ficheiros e abrir o ficheiro config.php e colocar os dados de acesso a base de dados. <b>Observação</b>: No MySQL Database, o primeiro campo representa o último campo do ficheiro config.php, o último campo do MySQL representa o primeiro campo do ficheiro.php e os dois campos do meio mantêm-se igual, por fim deve <b>salvar o ficheiro</b> config.php. <br>
  <br>
  <img src="https://drive.google.com/uc?export=view&id=1kPegSrhSqoYhjVkx-4EKYLfJNidz4H0l" alt="Ficheiro config.php" width="500">
  <img src="https://drive.google.com/uc?export=view&id=1V7JXsBCg7fHhZNZ6OtNIukvXxXVo2qm-" alt="Codigo do ficherio config.php" width="500">
  16. Para acabar deves aceder a página web, o link está no email enviado, ao criar a conta. <b>Observação</b>: Tem que colocar, depois do fim do link, o seguinte complemento "/nome da pasta/nome do ficheiro(neste caso "admin_page.php")" <br>
  <br>
  <img src="https://drive.google.com/uc?export=view&id=1lEAJFeYC2xduj8Egz_KpQYF6K4yP1sL_" alt="Link" width="500">
  17. Ver <a href="http://a14486.alojamento-gratis.com/ex03/admin_page.php" target="_blank">resultado final</a>. <br>
  <br>
  Feito por João Martins (a14486)
