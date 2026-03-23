# TPC3
## 11 de Março 2026

### Por:
    - Pedro Manuel Macedo Rebelo
    - a104091
<img src="../eu.png" alt="foto" width="300">

### Resumo:
    TPC6: uma App sobre cinema americano
	Cria uma orquestração de sereviços para implementar uma App sobre cinema:
		. Descarrega o dataset sobre cinema;
		. Depois de analisares o que se pede a seguir faz as alterações que achares necessárias ao dataset;
		. Carrega o dataset no MongoDB; deverás ter ficado com 3 coleções: filmes, atores e generos;
		. Cria uma API de dados minimalista sobre as 3 coleções;
		. À semelhança do que foi feito na aula, isola os teus serviços em containers docker e cria uma
		orquestração para a API de dados;
		. Cria um servidor aplicacional que responda aos seguintes pedidos:
			GET /filmes - responde com uma página HTML contendo uma tabela com os seguintes
			campos de filme: id, título, ano, número de atores no elenco e número de géneros associados
			ao filme; Cada linha deve ser um link para a página individual de filme;
			GET /filmes/:id - responde com uma página HTML contendo toda a informação de filme;
			GET /atores - responde com uma página HTML contendo uma tabela com os seguintes
			campos de ator: id, nome, número de filmes em que participou; Cada linha deve ser um link
			para a página individual de ator;
			GET /atores/:id - responde com uma página HTML contendo toda a informação de ator;
			GET /generos - responde com uma página HTML contendo uma tabela com os seguintes
			campos de género: id, designação, número de filmes associados ao género;
		. Cria um docker para interface;
		. Orquestra tudo num docker compose.
		
### Lista de Resultados
