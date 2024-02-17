# instalação e usos

OBS.: Antes de mais nada, você deverá baixar o poetry. Existem diversos blogs e vídeos que ensinam como fazer, fique a vontade para procurar e usar o melhor método para você.

Para fazer o uso com tudo configurado basta seguir os passos abaixo:

```
git clone https://github.com/ramoonmedeiro/tesseract-ocr.git
cd tesseract-ocr/
poetry shell
poetry install
```
Tudo será configurado e você já poderá rodar os notebooks da forma como desejar.

# Tutoriais básicos

1) *prepocessing.ipynb:*
- Tutorial sobre diversos pré-processamentos de imagens, como por exemplo: limiariazação, retirada de ruídos e etc.

2) *tesseract-example:*
- Tutorial básico de como extrair string de imagens ou saber sobre metadados.

# Projetos

Neste repositório existem dois projetos simples:


*Projeto 1:*
- Reconhecimento de texto em imagens de um diretório (busca por termos específicos). Aqui neste projeto foi mais uma motivação para quem deseja estudar essa ferramenta, em como utilizar o pytesseract juntamente com outras bibliotecas de visão computacional, para extrair texto e fazer extração de entidade nomeadas com o spaCy.


*Projeto 2:*

- Simulação de um scanner com python. Este projeto é mais avançado e trata-se de pegar imagens que estão fora de foco ou contexto e o resultado final parecer ser um scanner fidedigno da imagem.
