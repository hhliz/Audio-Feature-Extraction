﻿
# <h1> Projeto para Processamento de imagem


# <h2> Projeto: Extração de caracterı́sticas para classificação de áudios.


O objetivo deste projeto é implementar, comparar e conhecer as vantagens dos métodos existentes para descrever características baseadas em cor e textura para processar imagens geradas desde arquivos de audio .wav.

 
# <h2> Imagens:

Imagens de Espectrogramas no formato RGB gerados apartir dos áudios. Este é um conjunto de arquivos de áudio .wav, cada um contendo uma única palavra falada em inglês. Estas palavras são faladas por uma variedade de falantes diferentes. O conjunto de dados tem aproximadamente 65000 audios, organizados em pastas por palavras: "Yes", "No", "Up", "Down", "Left", "Right", "On", "Off", "Stop", "Go", "Zero", "One", "Two", "Three", "Four", "Five", "Six", "Seven", "Eight",  "Nine", "Bed", "Bird", "Cat", "Dog", "Happy", "House", "Marvin", "Sheila", "Tree", e "Wow".
Dataset [link aqui!](http://download.tensorflow.org/data/speech_commands_v0.01.tar.gz).






 

<a href="url"><img src="https://github.com/LizHuancapaza/Audio-Feature-Extraction/blob/master/imagens/2aa787cf_nohash_0.png" align="left" height="200" width="200" ></a>

<a href="url"><img src="https://github.com/LizHuancapaza/Audio-Feature-Extraction/blob/master/imagens/2aa787cf_nohash_1.png" align="left" height="200" width="200" ></a>

<a href="url"><img src="https://github.com/LizHuancapaza/Audio-Feature-Extraction/blob/master/imagens/3f170018_nohash_0.png" align="left" height="200" width="200" ></a>

<a href="url"><img src="https://github.com/LizHuancapaza/Audio-Feature-Extraction/blob/master/imagens/3f2b358d_nohash_4.png" align="left" height="200" width="200" ></a>

<a ></a>






# <h2> 

# <h2> Etapas:



    
    
1. Gerar os Espectrogramas (Imagens): Para gerar os espectrogramas vou empregar a transformada de furier e escalas logarı́tmicas para melhorar a visualização dos detalhes do sonido (palavra falada) no espectrograma. Depois teremos como resultado uma imagem com formato: .png 

2. Empregar métodos descritores de cor e textura para database "CORE 1K" e "Espectrogramas".
    * Descritores de cor
    
        * Border/Interior Classification (BIC)
    * Descritores de textura
    
        * Co-ocurrence Matrix
3. Finalmente para medir a qualidade empregarei a acurácia de classificação.

 
 
 

@LizHuancapaza :+1: 
