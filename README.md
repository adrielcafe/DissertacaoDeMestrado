<p align="center">
  <a href="https://github.com/adrielcafe/DissertacaoDeMestrado-LaTeX/raw/master/DissertaçãoMestradoAdrielCafé.pdf">
    <img src="https://github.com/adrielcafe/DissertacaoDeMestrado-LaTeX/raw/master/cover.png">
  </a>
</p>

*Clique na imagem para abrir o PDF*

## Resumo
> Integração da informação é uma área de pesquisa ativa a qual tenta-se criar mecanismos para extrair ou mesclar fontes de dados. Integração semântica é uma subárea, nela são utilizadas tecnologias da Web Semântica para tornar o processo de integração o mais inteligente e automático possível. 

> Para realizar uma integração semântica, são utilizadas ontologias que representam formalmente o vocabulário utilizado para descrever o conteúdo de fontes de dados. Por conta disso são frequentemente utilizadas para enriquecer o processo de integração. Bancos de dados relacionais são utilizados para armazenar e recuperar grandes quantidades de dados de forma rápida e eficiente. Devido a aplicação da estratégia relacional em diversos sistemas com propósitos diferentes, quando há a necessidade de fazê-los trocar dados (dentro de um mesmo domínio), utilizar uma estratégia de integração semântica é recomendado pela praticidade e versatilidade.

> Nesse sentido, este trabalho tem como objetivo propor uma arquitetura para integração semântica de fontes de dados heterogêneas dentro de um mesmo domínio. Esta arquitetura propõe a realização de uma integração virtual, mediada por consultas, entre ontologias e bancos de dados relacionais. 

> Como prova de conceito foi desenvolvido o Gryphon, um framework Java de código aberto que implementa a arquitetura proposta. O Gryphon Framework (semi) automatiza as principais atividades relacionadas a integração semântica: alinhamento de ontologias, mapeamento de banco de dados e reescrita de consultas. 

> Para demonstrar a capacidade e a praticidade de realizar integração semântica com a arquitetura proposta e o Gryphon Framework, foram realizados dois experimentos. No primeiro experimento foram criadas consultas por um biologo especialista do domínio biológico para ontologias formais ricamente axiomatizadas (Gene Ontology, Protein Ontology, Chemical Entities of Biological Interest e BioTopLite2). Essas ontologias foram utilizadas para integrar e consultar o banco de dados UniProt/SwissProt. No segundo experimento foram integradas duas ontologias (SIOC e rNews) e dois bancos de dados (Joomla e WordPress) do domínio de notícias utilizando a ontologia News como camada semântica.

> PALAVRAS-CHAVE: Integração Semântica, Integração de Dados, Alinhamento de Ontologias, Mapeamento de Banco de Dados, Reescrita de Consultas

# Abstract
> Integration of information is an active research area that attempts to create mechanisms to merge data sources, or retrieve data from distributed sources. Semantic integration as a subarea, frequently uses semantic web technologies to make the process of integrating the most intelligent and automatic as possible. 

> To perform a semantic integration, ontologies are used to formally represent the vocabulary used to describe the content of data sources. Ontologies are often used to enrich the process of integration. Relational databases are used to store and retrieve large amounts of data quickly and efficiently. Due to the application of relational strategy in various systems with different purposes when, when there is a need to make them exchange data (within the same domain), a semantic integration strategy is recommended by the practicality and versatility.

> In this sense, this work aims to propose an architecture for semantic integration of heterogeneous data sources within the same domain. With the architecture, it is proposed to conduct a virtual integration, mediated by queries, between ontologies and relational databases.

> As proof of concept, the Gryphon was developed. It is an open source Java framework which implements the proposed architecture. The Gryphon Framework (semi) automates key activities related to semantic integration:  alignment of ontologies, database mapping and query rewrite.

> To demonstrate the ability and practicality of performing semantic integration with the proposed architecture under Gryphon Framework, two experiments were conducted. In the first experiment queries were created by an expert in the biological domain to retrieve data integrated with the support of formal and richly axiomatized ontologies (Gene Ontology, Protein Ontology, Chemical Entities of Biological Interest and BioTopLite2). These ontologies were used to integrate and query the UniProt/SwissProt database. In the second experiment were integrated two ontologies (SIOC and rNews) and two databases (Joomla and WordPress) from news domain using the News ontology as semantic layer.

> KEYWORDS: Semantic Integration, Data Integration, Ontology Alignment, Database Mapping, Query Rewriting

## Gryphon Framework
![](https://github.com/adrielcafe/GryphonFramework/raw/master/images/gryphon.png)

O Gryphon é o resultado deste projeto. Ele é um framework open source que possibilita uma integração virtual, mediada por consulta, entre ontologias e bancos de dados relacionais simultaneamente.

[Repositório do Gryphon Framework](https://github.com/adrielcafe/GryphonFramework)


* * *
[![CIn-UFPE](https://github.com/adrielcafe/GryphonFramework/raw/master/images/cin.png)](http://www2.cin.ufpe.br)
[![UFPE](https://github.com/adrielcafe/GryphonFramework/raw/master/images/ufpe.png)](http://www.ufpe.br)

*Esta dissertação utilizou o [RiSEThesis](https://github.com/yguarata/risethesis) (template para LaTeX)*
