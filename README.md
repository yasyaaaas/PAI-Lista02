# PAI Lista 2 - Yasmin Cassemiro Viegas 

## Questão 1 - Comparação entre Algoritmos de Segmentação

### Algoritmos Implementados
- **Canny Edge Detection**: Segmentação por bordas
  - O Canny detecta bordas em imagens encontrando onde a intensidade das cores muda bruscamente. Ele é como um "contornador" inteligente que desenha linhas onde terminam objetos e começam outros
- **K-means Clustering**: Segmentação baseada em agrupamento
  - O K-means agrupa pixels parecidos. Se você pedir para ele encontrar 4 grupos (K=4), ele vai juntar todos os pixels similares em 4 "clusters" de cores

### Como Executar
#### Google Colab 
1. Faça upload do notebook `Q01.ipynb` para o Google Colab
2. Execute as células em ordem sequencial (1 a 11)
3. As imagens já estão incluídas na pasta `img/`

## Questão 2 - Representação Geométrica via Esqueletização

### Técnica Implementada
- **Esqueleto do Objeto (Skeleton)**: Representação do eixo medial preservando topologia e conectividade
  - O algoritmo de esqueletização "afina" o objeto até sobrar apenas sua linha central, preservando a forma básica e as conexões

### Como Executar
#### Google Colab
1. Faça upload do notebook Q02.ipynb para o Google Colab
2. Execute as células em ordem sequencial (1 a 9)
3. A imagem já está incluída na pasta `img/`
