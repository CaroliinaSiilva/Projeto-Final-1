Turismo em Portugal

Ultima atualização- 18 de Maio de 2021

Contexto:

No âmbito da unidade curricular Programação e Algoritmos II do 1.º ano do curso de Licenciatura de Comunicação e Design Multimédia, 2º semestre, sob orientação do docente João Orvalho, foi-nos solicitado a elaboração de um trabalho.
Com a composição deste projeto final podemos explorar e adquirir novos conhecimentos na área da programação.


Aplicação do repositorio:

O projeto permite a recolha/exposição de vários dados nomeadamente:
	
Fundamentação dos dados

A recolha de dados devidamente estruturados é crucial para o desenvolvimento do nosso projeto, no entanto grande parte dos dados encontrados tratam-se de dados com fraca qualidade e construídos indevidamente.

Posto isto, vimo-nos a ser obrigadas a proceder a uma limpeza dos dados, sendo que estes estavam em mau estado, por exemplo palavras em campos que deveriam ser numéricos e organização por tabela dos dados.

Sobre o tema escolhido para este projeto foi realemente dificil encontrar dados que estivessem em formato padrão, o que seria muito benéfico para o bom desenvolvimento deste trabalho.

Foi utlizando dois formatos de ficheiro, Json e CSV. O Json são representados como pares de valor-chave num formato semi-estruturado, este contém estruturas hierárquicas. O formato CSV são considerados semi-estruturadosnão mas não podem, naturalmente, representar dados hierárquicos ou relacionais.

No caso dos dados “Ano de Atendimento” estes foram importados através de sistema URL, a formac como estavam estruturados os dados fazia com que fosse impossível de ser lida em jupiter, para solucionar o nosso problema passamos a criação de um CSV padrão com os dados que queríamos utilizar corretamente organizados.

Sobre o tema escolhido para este projeto foi realemente dificil encontrar dados que estivessem em formato padrão, o que seria muito benéfico para o bom desenvolvimento deste trabalho.

Para a elavoração da nossa base de dados, foi nos aconcelhado importarmos sempre dados que estivessem em CSV padrão, no entanto muitos dos dados encontrados estavam em outros formatos. Como por exemplo xlsx, para conseguirmos utilizar estes dados com base no ficheiro "copia de despesas media de turistas" criamos uma tabela ("preços") com os dados e não importamos diretamente o ficheiro.

Departamo-nos com a falta de dados para a execução de exercicio relativos á longitude e á latitude, por isso importamos mais dados que não pertencem só a Portugal.

Estrutura:

	Organização repositório:
	Dormidas nº estadia.json— contém dados relativos ao número de estadias turísticas no ano de 2019.
	alojamento2019.csv— contém dados relativos a alojamentos em 2019 na localidade de Águeda.
	Ano atendimento.csv— contém dados extraídos da Câmara Municipal de Águeda que nos fornece o número de atendimentos no posto Turismo do mesmo ao longo de 10 anos.

API’s usados – notas técnicas:
	
	Esta base de dados utilizada neste reportório foi grande parte retirada de dados.gov.pt, no entanto utilizamos também dados fornecidos pela Camara Municipal de Agueda.
	
Dicionário de dados:

	dormidas - Conjunto de dados de como a informação foi extraída, acerca dos dados de dormidas de 2019 (tabela)
	dadosDormidas – Lista dos Dados de 2019 (tabela)
	dados2019 – Conjunto de dados sobre as informações de dormidas no ano 2019 (tabela)
	tamanho_tabela_1 – tamanho tabela dados 2019
	rslt_dados2019 - Dados de dormidas em Portugal no ano de 2019 (tabela) 
	dados – renomeação da tabela dados 2019 (tabela)
	alojamento - alojamentos de 2019 de Águeda (tabela)
	rslt_alojamentos – moradias que se enquadram na categoria motel (tabela)
	“line” – visualização do ficheiro em formato de objeto 
	atendimentos – atendimentos por ano no posto de Águeda (tabela)
	media_ at –  media de atendimentos durante 10 anos. 
	ultimos_anos – últimos dois anos de atendimentos (tabela)
	“plt.show” – gráfico representante dos anos de atendimentos
	ocupação- conjunto de dados relativos a taxas de ocupação (tabela)
	soma_quartos- soma dos quartos ocupados
	soma_cama- soma das camas ocupados
	estrelas_3- especificações do hotel com 3 estrelas
	d_ocp- descrição da tabela “ocupação” (tabela)
	preços- conjunto de dados relativos aos preços (tabela)

	
Bibliografia:

	https://dados.gov.pt/pt/
	https://dados.gov.pt/pt/datasets/r/b9b406ab-bc80-448f-8c47-406f66b4e48a
	https://dados.gov.pt/pt/datasets/r/029f7761-d427-404a-a639-a3eb1c83ffd8
	https://ckan.sig.cm-agueda.pt/dataset/antendimentos-no-posto-de-turismo-de-agueda/resource/a2abb35b-62b1-4b9f-87b4-5a3a67558626
