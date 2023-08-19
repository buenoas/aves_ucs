# Representativeness of bird species of high conservation concern in protected areas of Brazil

Este repositório possui os arquivos de dados e o código R para organizar e analisar os dados referentes ao trabalho *Representativeness of bird species of high conservation concern in protected areas of Brazil*.

Os arquivos são os seguintes:

* **CBRO_2021.txt**: Lista das aves do Brasil, segundo o Comitê Brasileiro de Registros Ornitológicos ([Pacheco, 2021](https://doi.org/10.1007/s43388-021-00058-x)). O arquivo corresponde à planilha "Lista Primária" do arquivo [2021.07.26 CBRO 2021 Zenodo Release.xlsx](https://zenodo.org/record/5138368/files/2021.07.26%20CBRO%202021%20Zenodo%20Release.xlsx?download=1), baixado em 2023-08-19 e disponível no repositório [Zenodo](https://zenodo.org/record/5138368). A planilha "Lista Primária" foi aberta no programa Excel, copiada e depois colada no programa Bloco de Notas para ser salva em formato ".txt", como texto separado por tabulações.

* **cnuc_2023_07**: Shapefile (polígonos) das Unidades de Conservação do Brasil, baixado em 19-08-2023 e disponível no [Portal de Dados Abertos](https://dados.gov.br/dados/conjuntos-dados/unidadesdeconservacao) sob o título "Polígno CNUC 2023_07". O arquivo "cnuc_2023_07.shp" foi aberto no programa QGIS (versão 3.22.3), convertido para o CRS "EPSG:4326  - WGS 84" e exportado no formato "ESRI Shapefile".

* **SALVE_Aves.txt**: Planilha de dados sobre as aves do Brasil disponível na plataforma [SALVE](https://salve.icmbio.gov.br). O arquivo ".csv" gerado pelo botão "Exportar tabela", que resultou da busca com o filtro "Grupo = Aves", foi baixado em 19-08-2023, importado no programa Excel, copiado e depois colado no programa Bloco de Notas para ser salvo em formato ".txt", como texto separado por tabulações.

* **Rcode**: código R utilizado para organizar e analisar os dados, escrito por Anderson Saldanha Bueno. O Rcode está em constante atualização.
