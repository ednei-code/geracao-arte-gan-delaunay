# geracao-arte-gan-delaunay
Este projeto de estudo explora a geração de arte utilizando Redes Adversariais Generativas (GANs) e o dataset DELAUNAY, com experimentos focados nos estilos dos artistas Vassily Kandinsky e Piet Mondrian. Os modelos foram implementados em Python, utilizando o Google Colab.
# Geração de Arte com GANs e Dataset DELAUNAY

Este projeto de estudo explora a aplicação de Redes Adversariais Generativas (GANs) para a geração de arte abstrata, utilizando um subconjunto do dataset DELAUNAY. Os experimentos foram conduzidos no ambiente Google Colab e implementados em Python com a biblioteca TensorFlow/Keras.

## Visão Geral

O objetivo principal foi experimentar a capacidade das GANs em aprender e replicar os estilos de dois artistas abstratos distintos presentes no dataset DELAUNAY:

* **Vassily Kandinsky:** Conhecido por suas composições expressivas e abstratas, com formas geométricas e orgânicas, e cores vibrantes.
* **Piet Mondrian:** Famoso por seu estilo neoplasticista, caracterizado por linhas retas horizontais e verticais, e o uso de cores primárias (vermelho, amarelo, azul) com branco e preto.

## Metodologia

O projeto envolveu as seguintes etapas:

1.  **Seleção e Pré-processamento do Dataset:** Utilização de um subconjunto do dataset DELAUNAY contendo obras dos artistas Vassily Kandinsky e Piet Mondrian. As imagens foram redimensionadas para 64x64 pixels e normalizadas para o intervalo \[-1, 1].
2.  **Implementação da Arquitetura GAN:** Foi utilizada uma arquitetura GAN convolucional (inspirada na DCGAN), composta por um gerador (com camadas convolucionais transpostas) e um discriminador (com camadas convolucionais).
3.  **Treinamento dos Modelos:** Os modelos foram treinados utilizando a função de perda Binary Cross-entropy e o otimizador Adam. O processo de treinamento foi realizado no Google Colab.
4.  **Geração e Visualização de Imagens:** Ao longo do treinamento, foram geradas imagens de amostra para monitorar o progresso e avaliar a capacidade do gerador em aprender os estilos dos artistas.

## Resultados

Os resultados dos experimentos de geração de imagens, embora apresentem características dos estilos dos artistas, ainda mostram limitações em termos de nitidez e fidelidade aos detalhes das obras originais. As imagens geradas podem apresentar um aspecto borrado, indicando a necessidade de ajustes na arquitetura da GAN, nos hiperparâmetros de treinamento ou em um treinamento mais extenso.

## Código

O código completo para este projeto (notebook Jupyter do Google Colab) está disponível neste repositório. Ele contém a implementação dos modelos GAN, o loop de treinamento e as etapas de pré-processamento dos dados.

## Citação do Dataset DELAUNAY

Agradecemos aos autores do dataset DELAUNAY por disponibilizarem este valioso recurso para a pesquisa. Se você utilizar este trabalho ou o dataset em suas próprias pesquisas, por favor, cite o seguinte artigo:

@article{gontier2022delaunay,
title={DELAUNAY: a dataset of abstract art for psychophysical and machine learning research},
author={Gontier, Camille and Jordan, Jakob and Petrovici, Mihai A},
journal={arXiv preprint arXiv:2201.12123},
year={2022}
}


## Contribuições

Contribuições para este projeto são bem-vindas. Sinta-se à vontade para abrir issues ou enviar pull requests com sugestões de melhorias, experimentos com outras arquiteturas ou ajustes nos hiperparâmetros.

## Licença

 MIT License

 ## Contato
 ednei.adgpo@gmail.com
 
 https://www.linkedin.com/in/ednei-cunha-vicente-551b64187/
