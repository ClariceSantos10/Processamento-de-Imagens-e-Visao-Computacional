# Processamento-de-Imagens-e-Visao-Computacional

## Descrição do Projeto
Este projeto utiliza a visão computacional para reconhecer e classificar objetos em tempo real utilizando uma câmera. Com o uso de um modelo de aprendizado de máquina treinado, o sistema é capaz de identificar objetos comuns e exibir a classificação dos objetos na tela do computador.

## Instruções de Instalação

###Arquivos Necessários:
O modelo treinado deve ser obtido utilizando o Teachable Machine (ou outra plataforma de treinamento de modelos de visão computacional).
O arquivo .h5 (modelo treinado) deve ser salvo na mesma pasta do código Python.

Dependências:
Instale as bibliotecas necessárias executando: pip install opencv-python numpy tensorflow

Organização dos Arquivos:
O repositório deve conter:
  |-- modelo_treinado.h5
  |-- script_principal.py
  |--/projeto_visao_computacional
  |-- README.md

## Instruções de Uso

Captura de Imagem:

Utilize um aplicativo de captura de webcam como Cheese (Linux) ou Camera (Windows) para testar as imagens antes da execução do código.

Alterando a Fonte de Vídeo:

No código, localize a linha onde a câmera é inicializada:

cap = cv2.VideoCapture(0)  # 0 para webcam interna, altere para 1, 2... conforme necessário

Se estiver usando uma câmera externa, ajuste o índice (0, 1, 2...) até encontrar o correto.

Execução do Código:

Rode o script Python correspondente para iniciar a detecção em tempo real:

python script_principal.py

Interpretação dos Resultados:

O sistema exibirá uma janela com a câmera ao vivo, mostrando o objeto identificado e sua porcentagem de confiança.

## Créditos

Este projeto foi desenvolvido com contribuição de colegas de equipe em sala de aula  e foi realizado no Laboratório de Sistemas de Informação da UFOPA.
