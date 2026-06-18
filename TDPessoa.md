# Thiago Daniel Pessoa
Desenvolvedor Back-End | Python & Dados
## Sobre mim
Desenvolvedor Back-End com foco em Python, automação e dados. Crio soluções que reduzem atividades manuais, aumentam a confiabilidade das informações e apoiam decisões operacionais por meio de sistemas, integrações e processamento de dados.

Ao longo da minha experiência, desenvolvi sistemas internos utilizados em produção, pipelines de extração de dados que reduziram horas de trabalho manual para minutos e formulários que já coletaram milhares de registros para análise operacional. Também atuei em projetos GIS para clientes internacionais, trabalhando com grandes volumes de dados geoespaciais.

Busco oportunidades para aplicar conhecimentos em desenvolvimento Back-End, automação e Engenharia de Dados, contribuindo com soluções práticas para desafios reais de negócio.

## 🎓 Formações  
- [Graduação - CST em Banco de Dados](docs/CSTBancoDeDados.pdf)  
- [Curso - Power BI para Business Intelligence e Data Science](docs/DSA_PowerBIParaBusinessIntelligenceEDataScience.pdf)  
- [Curso - Estatistica para Análise de Dados](docs/UniCSul_EstatisticaParaAnaliseDeDados.pdf)  
- [Curso - Formação Python Developer](docs/DIO_FormacaoPythonDeveloper.pdf)  
- [Curso - BootCamp: Ciência de Dados com Python](docs/DIO_BootcampCienciaDeDadosComPython.pdf)  
- [Curso - CS50p](docs/CS50P.pdf)  

## Tecnologias

Principais ferramentas utilizadas em projetos de desenvolvimento back-end, automação, análise de dados e geoprocessamento.

### Stack Principal

* **Python** (Pandas, GeoPandas, Requests, BeautifulSoup, Selenium)
* **SQL** (ANSI SQL, MySQL, PostgreSQL)
* **Power BI** (DAX, dashboards interativos, ShapeMap)
* **Git & GitHub**

### Automação e Dados

* ETL e processamento de dados
* Web Scraping
* OpenPyXL
* Google Apps Script
* Google Sheets

### Desenvolvimento de Aplicações

* Kotlin
* Tkinter
* MS Access + VBA
* Integração com APIs e serviços web

### GIS & Geodados

* GeoJSON, GPKG e KML
* QGIS
* Shapely
* MapShaper
* Google My Maps

### Ferramentas Complementares

* Excel Avançado
* Tableau (básico)
* Markdown
* GIMP

  
## Projetos em Destaque

Ao longo da minha trajetória, desenvolvi soluções internas, automações, aplicativos móveis e projetos GIS aplicados a cenários reais. Meu foco é utilizar tecnologia para reduzir trabalho manual, aumentar a confiabilidade dos dados e apoiar decisões operacionais.  

### Pipeline de Extração de Dados Operacionais (Python)
    Ferramenta de coleta automatizada para sistema legado, responsável por extrair, validar e persistir dados operacionais utilizados em análises internas.

> **Problema**  
> A plataforma original não disponibilizava todos os campos necessários para análise e exigia coleta manual demorada.
>  
> **Solução**  
> Desenvolvimento de pipeline de extração em Python com autenticação automatizada, coleta em lote, monitoramento visual da execução, tratamento de falhas e integração com banco de dados.
>  
> **Impacto**
> * Redução de horas de trabalho manual para poucos minutos.
> * Obtenção de campos não disponíveis na exportação nativa.
> * Base utilizada para análises operacionais e geração de indicadores.
>  
> **Stack**  
> Python, Requests, BeautifulSoup, Selenium, Pandas, PyODBC, Tkinter.

---
### Plataforma Mobile de Gestão Operacional (Kotlin)

    Aplicação Android desenvolvida para digitalizar processos operacionais executados em campo, reduzindo dependência de formulários em papel e aumentando a rastreabilidade das atividades realizadas pelas equipes.

> **Problema**  
> Os registros operacionais eram distribuídos entre formulários físicos, sistemas com limitações de preenchimento e controles manuais, dificultando auditorias, análises e acompanhamento em tempo real das operações.
>
> **Solução**  
> Desenvolvimento de uma plataforma mobile capaz de gerenciar a abertura e encerramento de plantões, composição de equipes, inspeções veiculares com registro fotográfico, controle de ocorrências, abastecimentos e monitoramento GPS contínuo.
>
> O sistema opera mesmo sem conexão constante, mantém persistência local dos dados e realiza sincronização periódica com serviços externos para atualização cadastral e compartilhamento de informações operacionais.  
> Contando com:  
> * Rastreamento GPS em segundo plano.
> * Geração de segmentos GIS para análise de deslocamentos.
> * Integração com Google Sheets para atualização de cadastros.
> * Sincronização de estado operacional em tempo real.
> * Detecção automática de deslocamentos não registrados.
> * Persistência local utilizando banco embarcado.  
>  
> **Impacto**  
> * Digitalização de processos anteriormente realizados em papel.
> * Coleta estruturada de dados operacionais.
> * Geração automática de trilhas GPS para análise geoespacial.
> * Redução de falhas de registro através de mecanismos automáticos de monitoramento.
> * Base preparada para indicadores operacionais, consumo de combustível e desempenho de equipes.  
>  
> **Stack**  
> Kotlin, ObjectBox, Google Sheets, Google Drive, JSON e GIS.
---
### Plataforma de Monitoramento Operacional (Kotlin)  
    Aplicação complementar desenvolvida para acompanhamento das equipes em operação e   visualização consolidada dos dados enviados pelos dispositivos de campo.

> **Problema**  
> As informações operacionais permaneciam dispersas entre formulários, registros locais e sistemas independentes, dificultando o acompanhamento das equipes durante o plantão.
>  
> **Solução**  
> Desenvolvimento de uma aplicação de monitoramento capaz de consolidar dados operacionais, visualizar informações históricas, acompanhar posicionamento geográfico das equipes e fornecer consultas em tempo real sobre o estado das operações.
>
> **Impacto**  
> * Centralização das informações operacionais.
> * Visualização de histórico e dados em tempo real.
> * Integração com os dispositivos utilizados em campo.
> * Estrutura preparada para dashboards e indicadores operacionais.
>
> **Stack**  
> Kotlin, ObjectBox, MapBox, WebView, Google Apps Script e APIs Web.

---

### Sistema de Gestão Operacional e Estoque (MS Access)  
    Desenvolvido para centralizar informações operacionais, controle de estoque, colaboradores, equipes e viaturas em uma única base de dados relacional.  
  
> **Problema**  
> Os processos eram distribuídos entre planilhas, controles manuais e conhecimento informal dos usuários.  
>  
> **Solução**  
> Modelagem de banco de dados relacional com mais de 20 tabelas, formulários de operação, autenticação de usuários, consultas analíticas e relatórios operacionais.
>  
> **Impacto**  
> * Implantado em ambiente real.
> * Utilizado para controle de estoque e insumos.
> * Estrutura preparada para expansão para RH, escalas, abastecimentos e ocorrências operacionais.
> * Projeto baseado em levantamento de requisitos realizado junto aos setores envolvidos.  
>  
> **Stack**  
> MS Access, VBA, SQL ANSI.

---

### Digitalização de Processos Operacionais (Google Forms & JotForm)

    Conjunto de formulários desenvolvidos para substituir processos realizados por mensagens em grupos de WhatsApp e registros manuais, transformando informações operacionais em dados estruturados para análise. 
> Acesse-os: 
> - [Formulário de Plantões](https://docs.google.com/forms/d/e/1FAIpQLScz0ZCZTzP2RIpmRJaq9HAGWwqfKTFJwCQ_NObu648BFSSy_g/viewform?usp=header)  
> - [Formulário de Abastecimento](https://form.jotform.com/261594685021662)  
>  
> **Problema**  
> Informações importantes sobre abertura de plantão e abastecimentos eram registradas por mensagens de texto, gerando erros de preenchimento, omissões de dados, inconsistências e dificuldade para consolidação de relatórios.
>
> **Solução**  
> Desenvolvimento de formulários digitais para registro padronizado das operações.
>
> O formulário de plantão realiza a coleta estruturada de informações sobre equipes, viaturas, quilometragem, condições operacionais e vistorias.
>
> O formulário de abastecimento registra dados operacionais e evidências fotográficas, incluindo painel do veículo e bomba de combustível, reduzindo falhas e aumentando a confiabilidade dos registros.
>
> **Impacto**  
> * Mais de 1.000 registros de plantão coletados.
> * Centenas de registros de abastecimento documentados.
> * Eliminação de inconsistências comuns em registros por mensagens.
> * Base de dados utilizada para relatórios mensais de frota, consumo e desempenho operacional.
>
> **Stack**  
> Google Forms, JotForm, Google Sheets e Power BI.

---
### Freelance GIS & Dados

Projetos desenvolvidos para clientes internacionais através da Fiverr.

**Trabalhos realizados**

* Correção e validação de GeoJSONs.
* Conversão de datasets governamentais.
* Desenvolvimento de geofences para plataformas logísticas.
* Painéis geográficos em Power BI.
* Ferramentas de conversão de coordenadas e polígonos.

**Destaques**

* Conversão de dataset governamental da Finlândia com aproximadamente 70 GB.
* Projetos de geofencing para operações em Phoenix, Maui e British Columbia.

**Stack**
Python, GeoPandas, Shapely, QGIS, Power BI, GeoJSON, KML, GPKG.


## 📬 Vamos conversar?
Aberto a oportunidades em Back-End, Dados e Automação.  
Busco aplicar experiência prática em ambientes de produção para gerar eficiência e insights de negócio.
[LinkedIn](https://www.linkedin.com/in/thiago-pessoa-190043128/) | [Discord](discordapp.com/users/336673313919074315) | [Email](mailto:thiago.d.pessoa@gmail.com)
