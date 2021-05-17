## Grupo ##

Adine Alves Pereira Filho

Gabriel Pinheiro Teodoro

Milena Mayara Ruy

## Trabalho do código de Huffman ##

Após clonar o repositório:

```bash
git clone https://github.com/gabrieltepin/pgm-compression.git
cd pgm-compression
```

E instalar o módulo _numpy_:

```bash
pip3 install numpy
```

Pode-se, então **codificar** e **decodificar** as imagens utilizando-se o algoritmo de Huffman e também calcular a razão sinal-ruído **PSNR** das compressões.

### Codificação ###


```bash
python3 codificador.py
```

O programa irá comprimir, utilizando o algoritmo de Huffman, cópias das imagens pré-definidas no diretório _images_ em formato _.pgm_ para o formato _.huff_, no mesmo diretório _images_, e o valor dos comprimentos médios das palavras-código após a compressão de cada imagem será exibido no terminal.

### Decodificação ###

```bash
python3 decodificador.py
```

O programa deve recuperar cópias das imagens codificadas no diretório _images_ em formato _.huff_ de volta para o formato _.pgm_, no mesmo diretório _images_.

### PSNR ###

```bash
python3 psnr.py
```

Como a compressão de Huffman é sem perdas, não há ruído no processo e, portanto, a razão PSNR tende ao infinito.
