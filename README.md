# Criando um Pacote de Processamento de Imagens com Python

O objetivo desse projeto foi criar um pacote Python e publicar no PyPI. Como módulo do pacote, foi utilizado um projeto feito anteriormente que descolore imagens.

[Link do pacote no PyPI](https://pypi.org/project/monochrome-dionny/)

# Monochrome Dionny
Esse pacote permite transformar as cores de uma imagem em tons de cinza ou binarizadas em preto e branco.

## Descrição
O objetivo da criação desse pacote foi para experienciar e aprender a como utilizar o PyPI.

O pacote contem duas funções:
 - Acinzentar imagem: Transforma as cores da imagem em tons de cinza
 - Binarizar imagem: Transforma as cores da imagem em preto e branco

A imagem será salva com o sufixo "cinza" ou "binarizada" de acordo com a função utilizada.

## Instalação
```
pip install monochrome-dionny
```

## Uso
### Acinzentar imagem
```python
import monochrome_dionny as monodio

camimho_imagem = r"C:\Users\UserA\Imagens\dio.jpg"

monodio.acinzentar_imagem(camimho_imagem)
```

### Binarizar imagem
```python
import monochrome_dionny as monodio

camimho_imagem = r"C:\Users\UserA\Imagens\dio.jpg"

monodio.binarizar_imagem(camimho_imagem)
```

## Cuidados
Certifique-se de adiconar um "r" antes do caminho da imagem, isso evitará problemas com as "\\".

```python
camimho = r"C:\Users\UserA\Imagens\dio.jpg"
```

## Imagens

### Original
---
<img src="/images/dio.jpg" width="300">

### Cinza
---
<img src="/images/dio_cinza.jpg" width="300">

### Binarizada
---
<img src="/images/dio_binarizada.jpg" width="300">
