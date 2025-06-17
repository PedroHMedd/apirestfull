# apirestfull
Com o arquivo baixado, no htdocs e com xampp ligado.
Abra o VSCODE e baixe a extensão thunder client
No navegador use o link para hostear api localmente
http://localhost/apifilmesseries/index.php
Verifique carregou, se não, o problema pode ser no seu xampp ou em algum erro de digitação no link
No arquivo index.php tem-se a requisicao GET
O data.json serve apenas para armazenar os dados
No thunder client crie 4 requisições com o seguinte link também http://localhost/apifilmesseries/index.php
# ATENÇÃO PARA QUALQUER REQUISIÇÃO DEVE-SE USAR O ID, exemplo de exclusão de um filme, no request delete use: http://localhost/apifilmesseries/index.php?id=1
Ja no request de um POST por exemplo,
no json use:   
{
    "titulo": "Titulo do filme",
    "categoria": "Filme/Serie"
}
