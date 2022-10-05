<<<<<<< HEAD
# Credos da Cidade


Fortaleza tem cerca de 2,5 milhões de habitantes e, no último censo demográfico (2010), pouco mais de 162 mil pessoas declararam-se sem religião. Mas, atualmente, não é possível saber exatamente quantas são e onde estão localizadas de fato todas as igrejas, os templos evangélicos, as mesquitas, sinagogas, os centros espíritas, os de práticas budistas e os terreiros de umbanda e candomblé espalhados no território da Cidade.

Durante quatro meses, a Central de Jornalismo de Dados do **O POVO** (DATADOC) trabalhou em dados sobre benefícios concedidos a templos religiosos na Capital obtidos via Lei de Acesso à Informação (LAI) para produzir o [Especial Credos da Cidade](https://mais.opovo.com.br/reportagens-especiais/credos-da-cidade).

Por fim, foi possível chegar a um indicativo de mapa da fé na Capital, e ele é excludente das religiões de matriz africana e reducionista das práticas espíritas e outras religiosidades; mas contundente ao mostrar a presença evangélica nos bairros com IDH mais baixo e católica nas regiões mais centrais da Cidade.

Como resultado dessa investigação, foi publicada uma série de cinco matérias entre os dias 28 de janeiro e 21 de fevereiro de 2022. Acesse cada reportagem na tabela a seguir.


| EP | Data de publicação | Reportagem |
| -------- | -------- | -------- |
| 1 | 28/01/2022 | [O mapa da fé em Fortaleza: um caminho incerto, obscuro e excludente](https://mais.opovo.com.br/reportagens-especiais/credos-da-cidade/2022/01/28/o-mapa-da-fe-em-fortaleza-um-caminho-incerto-obscuro-e-excludente.html) |
| 2 |  04/02/2022 | [A cobrança da fé: as dívidas e o que o fisco não vê](https://mais.opovo.com.br/reportagens-especiais/credos-da-cidade/2022/02/04/a-cobranca-da-fe-as-dividas-e-o-que-o-fisco-nao-ve.html) |
| 3 | 08/02/2022 | [Universidade, construtora e banco ganham imunidade de impostos como se fossem igrejas](https://mais.opovo.com.br/reportagens-especiais/credos-da-cidade/2022/02/08/universidade-construtora-e-banco-ganham-imunidade-de-impostos-como-se-fossem-igrejas.html) |
| 4 | 14/02/2022 | [No CE, 3% dos casos de intolerância religiosa foram a julgamento](https://mais.opovo.com.br/reportagens-especiais/credos-da-cidade/2022/02/14/no-ce-3-dos-casos-de-intolerancia-religiosa-foram-a-julgamento.html) |
| 5 | 21/02/2022 | [Ontem e hoje: o estigma que rodeia as religiões afrobrasileiras](https://mais.opovo.com.br/reportagens-especiais/credos-da-cidade/2022/02/21/ontem-e-hoje-o-estigma-que-rodeia-as-religioes-afrobrasileiras.html) |

---


## Metodologia

Para a produção do especial Credos da Cidade, a DATADOC fez análises e mapeamentos dos credos existentes em Fortaleza, a partir dos dados da Secretaria Municipal das Finanças (Sefin) e da Superintendência da 3ª Região Fiscal da Receita Federal do Brasil.

A categorização das religiões usada pelo Instituto Brasileiro de Geografia e Estatística (IBGE) foi norteadora do trabalho de classificação dos templos pela Central. Mais detalhes desta análise podem ser observados em dois relatórios distintos, listados abaixo. 


### Relatórios

* [Análise exploratória: Dados de templos religiosos com imunidade tributária em Fortaleza (CE)](https://docs.google.com/document/d/1YJoWsp6kqZd5umcpybZiXI9rSBZetMeV7KGvDf1GWy0/edit?usp=sharing) concedida pela Secretaria Municipal das Finanças (Sefin).
* [Análise de Dados Públicos CNPJ, da Receita Federal](https://docs.google.com/document/d/1u-cwTM_sQO2UtJcElurrbmkkJXWI_i94iTM6seXRKLk/edit?usp=sharing), e cruzamento com dados de templos religiosos com imunidade tributária em Fortaleza

---

## Arquivos gerados
Nas pastas [`notebooks`](https://github.com/datadoc-opovo/credos-da-cidade/tree/main/notebooks) e [`bases_tratadas`](https://github.com/datadoc-opovo/credos-da-cidade/tree/main/bases_tratadas) é possível localizar o conjunto de códigos, dados agregados e diferentes visualizações exploradas no Especial Credos da Cidade.

Obs: Todos os arquivos listados em ferramentas *Google* (documentos e planilhas) possuem equivalentes abertos (em formato csv ou pdf) disponíveis nas pastas [`arquivos complementares`](https://github.com/datadoc-opovo/credos-da-cidade/tree/main/arquivos_complementares) e [`relatorios`](https://github.com/datadoc-opovo/credos-da-cidade/tree/main/arquivos_complementares/relatorios).

## Fonte e coleta de dados

* [Estabelecimentos e Empresas](https://www.gov.br/receitafederal/pt-br/assuntos/orientacao-tributaria/cadastros/consultas/dados-publicos-cnpj) — Receita Federal
* [Organizações religiosas de Fortaleza inscritas na dívida ativa da União](https://github.com/datadoc-opovo/credos-da-cidade/blob/main/bases_originais/divida_ativa_uniao.csv) — Receita Federal
* [Parcelamento da dívida ativa da União](https://github.com/datadoc-opovo/credos-da-cidade/blob/main/bases_originais/parcelamentos_divida_ativa_uniao.csv)
* [Templos com imunidade e isenção tributária em Fortaleza (CE)](https://github.com/datadoc-opovo/credos-da-cidade/blob/main/bases_originais/datasetSEFIN.csv) — Secretaria Municipal de Finanças (Sefin)
* [Bairros de Fortaleza](https://github.com/datadoc-opovo/credos-da-cidade/blob/main/bases_originais/bairrosFortaleza.geojson)

--- 

## Visualizações

#### **Episódio 1** - O mapa da fé em Fortaleza: um caminho incerto, obscuro e excludente

1. [80% das 819 concessões de imunidade tributária em Fortaleza são para evangélicos e católicos](https://public.flourish.studio/visualisation/8288556/) 
2. [Templos Religiosos por bairro de Fortaleza](https://datadoc-opovo.github.io/credos-da-cidade/embeds/mapa_sefin.html)
3. [Registros de templos religiosos em Fortaleza](https://public.flourish.studio/visualisation/8418231/)
4. [Projeção dos cadastros de templos religiosos em Fortaleza](https://datadoc-opovo.github.io/credos-da-cidade/embeds/projecao.html)
5. [Em Fortaleza, os dados da Sefin apontam que 108 bairros possuem templos religiosos, mas nenhum de matriz africana](https://public.flourish.studio/visualisation/8288230/)

#### **Episódio 2** - A cobrança da fé: as dívidas e o que o fisco não vê

1. [Evolução da dívida ativa da União](https://public.flourish.studio/visualisation/8441439/)
2. [Dez maiores devedoras da União em termos de inscrições na dívida ativa](https://public.flourish.studio/visualisation/8442031/)
3. [Conheça os 5 responsáveis pelas organizações religiosas com as maiores dívidas ativas e o seu vínculo com outras 23 empresas de setores variados](https://public.flourish.studio/visualisation/8609618/)
4. [22 templos religiosos no cadastro de imunidade da Sefin que não constam nos respectivos endereços declarados ao órgão municipal](https://datadoc-opovo.github.io/credos-da-cidade/embeds/end_inexistentes.html)
5. [Evolução dos registros de templos religiosos junto à Receita Federal](https://public.flourish.studio/visualisation/8593485/)

#### **Episódio 3** - Universidade, construtora e banco ganham imunidade de impostos como se fossem igrejas

1. [Em vermelho no mapa estão os 16 beneficiários da imunidade de IPTU que são empresas privadas e sem atividade religiosa. Em azul, o restante da amostra identificada pela DATADOC que também destoa da finalidade](https://datadoc-opovo.github.io/credos-da-cidade/embeds/templos_sem_definicao.html)
2. [Saiba mais sobre os templos com imunidade tributária classificados pela central DATADOC ](https://datadoc-opovo.github.io/credos-da-cidade/embeds/templos_categorizados.html)
3. [Principais igrejas com imunidade tributária em Fortaleza](https://public.flourish.studio/visualisation/8541661/)
4. [Em 10 anos, Fortaleza triplica valor dos benefícios fiscais a templos religiosos](https://public.flourish.studio/visualisation/8541695/)

#### **Episódio 4** - No CE, 3% dos casos de intolerância religiosa foram a julgamento

1. [Procedimentos relacionados à intolerância religiosa no Ceará, de 2017 a 2021](https://public.flourish.studio/visualisation/8654301/)

#### **Episódio 5** - Ontem e hoje: o estigma que rodeia as religiões afrobrasileiras

1. [Linha do tempo: assim nos contaram sobre os povos de terreiros](https://datadoc-opovo.github.io/credos-da-cidade/embeds/timeline/)
2. [73% dos procedimentos relacionados à intolerância religiosa no Ceará não tiveram resultado efetivo](https://public.flourish.studio/visualisation/8654519/)

---

<!-- ---

## Como utilizar

Para executar o notebook com a coleta e processamento dos dados, é necessário um ambiente com Python3 e dependências que podem ser instaladas via Pip:

```
!pip install 
!pip install 
!pip install 
``` -->

## A Central DATADOC

A Central de Jornalismo de Dados do **O POVO** (DATADOC) alia tecnologia e técnicas diversas de análises de dados para produzir um jornalismo de precisão para que você forme sua opinião com segurança. Nosso objetivo é fazer com que todos tenham acesso aos dados utilizados nas notícias que produzimos.

A DATADOC é composta por uma equipe de três jornalistas (sendo uma infografista), uma desenvolvedora front-end e um cientista da computação que coletam, enriquecem e disponibilizam as bases e códigos de cada reportagem para um jornalismo transparente e baseado em evidências.

---

**🔥📰👩🏻‍💻 Se você gostou do nosso material, apoie assinando o OP+ e acompanhando o nosso trabalho.**

**📝📨 Para feedback, dúvidas ou sugestões: datadoc@opovodigital.com**

---

🙍🏻‍♀️🙍🏽‍♀️🙍‍♀️🙍🏿‍♀️ Confira também outras produções recentes da Central DATADOC: Com o especial ***#ACorDaDor***, mostramos como o Ceará ignora a raça das mulheres vítimas de violência doméstica, comprometendo políticas públicas. O material está [disponível no **O POVO+**](https://mais.opovo.com.br/reportagens-especiais/violencia-contra-mulher-dados).

###### tags: `DATADOC`
=======
# Projeto Credos da Cidade

Neste repositório estão disponíveis todas as bases de dados utilizadas, os notebooks desenvolvidos para análise e tratamento dos dados, tabelas agregadas e algumas das visualizações utilizados na série de reportagens que compoem o especial Credos da Cidade. Esta é uma forma de garantir a transparência, reprodutibilidade e credibilidade dos nossos métodos.  

Em caso de dúvidas ou sugestões, entre em contato: **datadoc@opovodigital.com.br**

## Análises, códigos e visualizações:

 - Nas pastas [Notebooks]() e [Bases_Tratadas]()  é possível localizar o conjunto de códigos, dados agregados e diferentes visualizações exploradas neste projeto. Além disso, é possível conhecer a metodologia detalhada do projeto nos seguintes documentos:  
	 - [**Este documento**](https://docs.google.com/document/d/1YJoWsp6kqZd5umcpybZiXI9rSBZetMeV7KGvDf1GWy0/edit?usp=sharing)  apresenta uma análise exploratória e a metodologia para classificação por religião do conjunto de dados de templos religiosos com imunidade tributária concedida pela Secretaria Municipal das Finanças ([SEFIN](https://www.sefin.fortaleza.ce.gov.br/)), em Fortaleza-CE. A base disponibilizada contém Inscrição, Contribuinte, Endereço do Imóvel, Classificação e Benefício de 819  locais.  
	 - [**Este documento**](https://docs.google.com/document/d/1u-cwTM_sQO2UtJcElurrbmkkJXWI_i94iTM6seXRKLk/edit?usp=sharing) apresenta a metodologia e os resultados iniciais da análise de [dados públicos CNPJ, da Receita Federal](https://www.gov.br/receitafederal/pt-br/assuntos/orientacao-tributaria/cadastros/consultas/dados-publicos-cnpj), especificamente os dados das tabelas Dados Abertos CNPJ EMPRESA 1 à 10 e Dados Abertos CNPJ ESTABELECIMENTO 1 à 10, baixados em 29 de Outubro de 2021. O dicionário dos dados está disponível neste link e a base e suas respectivas informações estão disponíveis nesta pasta.  A base de dados de [Sócios das Empresas Brasileiras](https://brasil.io/dataset/socios-brasil/empresas/), correlata aos dados da Receita e disponibilizada de maneira acessível pela Brasil.io, também foi utilizada. Com download em 29/11/2021. 

\*Todos os arquivos listados em ferramentas *Google* (documentos e planilhas) possuem equivalentes abertos (em formato csv ou pdf) na pasta [arquivos complementares](). 

## Principais [bases de dados]() utilizadas 

 - [Estabelecimentos e Empresas (Receita Federal)]((https://www.gov.br/receitafederal/pt-br/assuntos/orientacao-tributaria/cadastros/consultas/dados-publicos-cnpj))
 -  Organizações religiosas de Fortaleza inscritas na dívida ativa da União (Receita Federal)
 - Templos com imunidade e isenção tributária em Fortaleza - CE (SEFIN)

 ## Entre em contato com a Central DATADOC !

 Em caso de dúvidas, sugestões, denúncias ou outros apontamentos, entre em contato: [datadoc@opovodigital.com](mailto:datadoc@opovodigital.com)	
![Marca da Central de Jornalismo de Dados do Jornal O POVO- DATADOC](/assets/datadoc_logo_cor.png)
>>>>>>> 87b77b288956ea2bb7dde73ebf1aafddf29a29fa
