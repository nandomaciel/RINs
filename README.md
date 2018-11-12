# RINs

## Autores: 

Eulle Araújo

Fernando Maciel

## Como testar novas estruturas 

1 - Tem que pegar o xml da estrutura que você deseja no site do RING 2.0 .
2 - Depois que você baixou o .xml , você copia o nome do arquivo e coloca no script "graphml_json.py" ( É necessário abrir o script para colar o nome do arquivo .xml .
3 - Depois de executar o script , será criado um arquivo .json chamado "YourFile.json".
4 - Com o .json criado , é necessário você colar o nome do arquivo "YourFile.json" no script que está em "js/code.js" na linha de código que tem "d3.json("nome_do_arquivo")" , ou você pode pegar o .json criado e colocar algum servidor, como por exemplo o ```https://gist.github.com/``` , e depois pegar o link gerado ( clicando no botão raw ) e colocar no mesmo local que foi comentado anteriormente.
5 - Por fim , acesse o arquivo "supersimple.html" .

