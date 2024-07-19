# Visualização e Processamento de Dados Geoespaciais

Bem-vindx ao repositório do tutorial **Visualização e Processamento de Dados Geoespaciais: Uma Introdução Prática**, apresentado no evento **Python Nordeste 2024**. Aqui contém todos os notebooks, scripts e conjuntos de dados utilizados. O objetivo deste tutorial é demonstrar técnicas e ferramentas para manipulação e visualização de dados geoespaciais no Python aplicadas no contexto de avaliação de políticas públicas para redução de desigualdades socioespaciais.

## Sumário

- [Sobre](#sobre)
- [Instalação](#instalação)
- [Notebooks](#notebooks)
- [Bibliotecas Utilizadas](#bibliotecas-utilizadas)
- [Como Contribuir](#como-contribuir)
- [Licença](#licença)

## Sobre

Este repositório contém dois notebooks distintos:

- **People Near Bike Lanes (PNB):** Este notebook apresenta um estudo sobre o indicador PNB, que mede a acessibilidade dos habitantes de um município à infraestrutura cicloviária.

- **Normalized Difference Vegetation Index (NDVI):** Este notebook avalia o indicador NDVI, que mede a densidade de vegetação em uma área por meio de imagens de satélite. O foco é analisar a proximidade da vegetação nas áreas urbanas de Natal e sua relação com locais onde os habitantes estão, que possibilita o estudo das áreas das cidades que diretamente contribuem para a drenagem urbana, evitando o surgimento de ilhas de calor e absorção de parte da poluição gerada pelas atividades dos arredores. A análise segue a [metodologia](https://observatorio.responsivecities.com/?indicador=meio-ambiente) proposta pelo [Instituto Cidades Responsivas](https://www.responsivecities.com/).

## Instalação

### Pré-requisitos

- Python 3.7 ou superior
- Jupyter Notebook ou Google Colab

### Passos para Instalação

1. Clone o repositório:

    ```bash
    git clone https://github.com/PedroFlorencioNeto/visgeo.git
    cd visgeo
    ```

2. Crie e ative um ambiente virtual:

    ```bash
    python -m venv env
    source env/bin/activate  # Para Windows, use `env\Scripts\activate`
    ```

3. Instale as dependências:

    ```bash
    pip install -r requirements.txt
    ```

4. Inicie o Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

## Notebooks

Os notebooks deste repositório são organizados conforme os tópicos apresentados no evento:

1. **Acesso a Infraestrutura Cicloviária**
    - `01_InfraestruturaCicloviaria.ipynb`

2. **Análise do NDVI**
    - `02_NDVIAnalysis.ipynb`

## Bibliotecas Utilizadas

Este projeto utiliza diversas bibliotecas populares para processamento e visualização de dados geoespaciais em Python:

- [Pandas](https://pandas.pydata.org/)
- [Geopandas](https://geopandas.org/)
- [H3](https://h3geo.org/)
- [Plotly](https://plotly.com/)
- [Folium](https://python-visualization.github.io/folium/)
- [Shapely](https://shapely.readthedocs.io/)
- [Matplotlib](https://matplotlib.org/)
- [Contextily](https://contextily.readthedocs.io/en/latest/)

## Como Contribuir

Contribuições são bem-vindas! Siga os passos abaixo para contribuir:

1. Fork o repositório.
2. Crie uma nova branch para suas modificações:
    ```bash
    git checkout -b minha-nova-feature
    ```
3. Faça suas alterações e commit:
    ```bash
    git commit -m "Adiciona nova feature"
    ```
4. Push para a branch:
    ```bash
    git push origin minha-nova-feature
    ```
5. Abra um Pull Request.

## Licença

Este projeto é licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

---

Esperamos que você aproveite este projeto e que ele seja útil para aprender mais sobre processamento e visualização de dados geoespaciais com Python!

