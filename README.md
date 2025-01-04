# sistema_de_reconhecimento_facial

Desenvolvimento de um sistema de reconhecimento facial utilizando Python. 

Utilizei o passo a passo do tutorial do professor Dr. Diego Bruno tech na DIO. 
<https://www.youtube.com/watch?v=EHVrtO9FTEg>

Instala-se as bibliotecas.

Cria uma função para funcionar a webcam de nosso computador no colab.

Redimensiona a saída dos pesos do google colab para ajustá-la ao vídeo.

Faz retorno para que a imagem seja capturada ao clicar em capturar.

Depois é feita a leitura, o redimensionamento e a imagem é exibida.

Usa o transfer learning para carregar o modelo de rede de detecção facial pré-treinado do disco.

Normaliza a imagem.

Filtra detecções fracas garantindo que a "confiança" seja de no mínimo 50% e desenha a caixa que vai delimitar a imagem reconhecendo a face. 

O resultado é mostrado em imagem. 
	

