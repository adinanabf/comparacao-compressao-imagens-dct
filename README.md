# Comparação de métodos de compressão de imagens baseados na Transformada Discreta de Cosseno (DCT)

![Figura ilustrando o dataset do projeto.](/src/dataset/img_dataset.png "Dataset do projeto.")

Repositório dedicado ao compartilhamento do código desenvolvido durante a realização do projeto de Iniciação Científica "Estudo e comparação de técnicas de compressão de imagens baseados em Transformadas Discretas" (2020-2021), em parceria com o [Prof. Dr. Kenji Nose Filho](mailto:kenji.nose@ufabc.edu.br).

Os métodos de compressão baseados na DCT comparados foram os seguintes:

- Mascaramento
    - Quadrado
    - Triangular
- Quantização
    - Tabelas JPEG Standard
    - Tabelas Kendinan (autorais)

Os métodos foram aplicados sob diversas taxas de compressão. A análise dos resultados foi baseada na quantidade de informação preservada e no grau de degradação da imagem reconstruída. Para as cinco classes de imagens estudadas - retrato, paisagem, padrões geométricos, tipografia e contexto social, o método que obteve o melhor desempenho, em geral, foi o da **quantização com Tabelas Kendinan**. As tabelas Kendinan são tabelas de quantização criadas pelos autores do projeto.

Para mais detalhes acerca da IC e da metodologia empregada nos experimentos, leia o artigo publicado na conferência SIBGRAPI 2022: `Paper_AdinanFilho_SIBGRAPI_WUW_2022.pdf`, ou ainda a apresentação de slides do projeto utilizada no evento SIBGRAPi: `ppt_Adinan_SIBGRAPI.pdf`. Ambos os documentos estão disponíveis neste repositório.

A interface educacional referente ao presente estudo pode ser acessada por meio do arquivo `./src/Interface_Interativa_DCT.ipynb`, também disponível neste repositório. Abaixo, figura ilustrando o funcionamento da interface educacional.

![](/images/interface.png "Interface educativa para comparação de métodos de compressão de imagens utilizando a DCT.")