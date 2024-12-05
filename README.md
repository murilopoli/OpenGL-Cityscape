# OpenGL Cityscape
Uma simulação 3D de uma cidade criada com Python, OpenGL e Pygame, incluindo prédios, carros em movimento, árvores, uma pirâmide e um sol que ilumina toda a cena. Este projeto explora conceitos básicos de gráficos 3D, texturização, iluminação e movimentação de objetos.


## 🏗️ Funcionalidades
- **Prédios**: Estruturas tridimensionais texturizadas.
- **Carros em movimento**: Objetos animados que trafegam na cena.
- **Árvores**: Estruturas com troncos cilíndricos e copas esféricas.
- **Pirâmide**: Estrutura adicional para variedade arquitetônica.
- **Sol**: Representado por uma esfera iluminada, que também funciona como fonte de luz.
- **Câmera controlável**: Movimente e gire a câmera usando o teclado.


## 🖥️ Pré-requisitos
Certifique-se de ter as seguintes ferramentas instaladas no seu sistema:
- Python 3.8 ou superior
- Bibliotecas:
  - `pygame`
  - `PyOpenGL`
  - `Pillow`


Para instalar as dependências, use o comando:
pip install pygame PyOpenGL Pillow


🚀 Como executar
Clone este repositório:
git clone https://github.com/seuusuario/opengl-cityscape.git
cd opengl-cityscape
Certifique-se de que as imagens de textura (chao.jpg, predio.jpg, carro.jpg, etc.) estão na mesma pasta do script.


Execute o script principal:
python main.py
Use as setas do teclado para movimentar a câmera:

Seta para cima: Avançar
Seta para baixo: Recuar
Seta para esquerda: Girar para a esquerda
Seta para direita: Girar para a direita


📂 Estrutura do Projeto
opengl-cityscape/
│
├── main.py               # Script principal
├── chao.jpg              # Textura para o chão
├── predio.jpg            # Textura para os prédios
├── carro.jpg             # Textura para o carro 1
├── carro2.jpg            # Textura para o carro 2
├── tronco.jpg            # Textura para o tronco das árvores
├── folha.jpg             # Textura para as folhas das árvores
├── piramide.jpg          # Textura para a pirâmide
└── sol.jpg               # Textura para o sol


🛠️ Funcionalidades Futuras
Adicionar mais elementos arquitetônicos.
Implementar iluminação dinâmica com variação temporal.
Incluir sons para dar vida à cidade.


🤝 Contribuições
Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.


📝 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
