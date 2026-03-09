# TPC4
## 25 de Fevereiro de 2026

### Por:
    - Pedro Manuel Macedo Rebelo
    - a104091
<img src="../eu.png" alt="foto" width="300">

### Resumo:
    . Colocação do dataset dos EMD no json-server;
    . Criação de um servidor aplicacional para responder aos pedidos:
        GET / ou GET /emd - responde com uma página principal onde consta uma tabela com os
        EMD; a tabela apresenta os campos: nome do atleta, data, modalidade, resultado;
        GET /emd/:id - responde com uma página composta por um card com toda a informação
        do EMD;
    Da tabela deve ser possível saltar para a página de um EMD clicando na respetiva linha;
    A página do EMD deverá ter um botão "Voltar" no seu rodapé;
    Como extra na aula, poderás acrescentar dois botões na parte superior da tabela, um para
    ordenar os registos por data de forma decrescente e outro para os ordenar por nome de forma
    crescente.
    Como trabalho de casa deverás suportar as seguintes rotas:
        GET /emd/registo - responde com o formulário para recolha dos dados do novo EMD;
        GET /emd/editar/:id - responde com o formulário para edição dos dados do registo
        selecionado;
        GET /emd/apagar/:id - apaga o registo selecionado e redireciona para a página principal;
        GET /emd/stats - responde com uma página (layout à tua escolha) com as distribuições dos
        registos por: sexo, modalidade, clube, resultado, federado;
        POST /emd - insere o registo na base de dados e redireciona para a página principal;
        POST /emd/:id - altera o registo na base de dados e redireciona para a página principal.

### Lista de Resultados
* [Lista de EMDS](output/trlist.html)
* [1 EMD](output/emdID.html)
* [Forms de adicionar](output/form.html)
