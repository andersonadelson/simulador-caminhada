# Simulador de Caminhada

Este projeto é uma simples simulação de caminhada utilizando HTML, CSS e JavaScript. Nele, um personagem é animado com imagens para simular o movimento de andar para a direita ou para a esquerda utilizando as setas do teclado.

## Funcionalidades

- **Movimento Direcional:** O personagem se move para a direita ou para a esquerda conforme a tecla pressionada.
- **Animação de Caminhada:** Alterna entre imagens para simular os passos do personagem.
- **Transformação de Imagem:** Se o personagem se mover para a esquerda, a imagem é invertida para manter a direção correta.

## Estrutura do Projeto

```
simulador-caminhada/
│
├── index.html        # Arquivo principal com o código da simulação  
├── anda-01.jpg       # Imagem representando o primeiro passo de caminhada
├── anda-02.jpg       # Imagem representando o segundo passo de caminhada
├── parado.jpg        # Imagem do personagem parado  
└── README.md         # Este arquivo
```

## Como Usar

1. **Clone o Repositório**
   ```bash
   git clone https://github.com/andersonadelson/simulador-caminhada.git
   ```
2. **Abra o Projeto**
   
   Abra o arquivo `index.html` em seu navegador ou através de um servidor local.
   
3. **Controle o Personagem**
   
   - Pressione a seta **direita** para mover o personagem para frente.
   - Pressione a seta **esquerda** para mover o personagem para trás.
   - Ao liberar a tecla, o personagem retorna ao estado parado.

## Configurações Adicionais

- **Velocidade de Animação:** A velocidade de alternância dos frames pode ser ajustada modificando o intervalo no JavaScript.
- **Posição Inicial:** A posição inicial do personagem pode ser alterada no CSS ou diretamente no JavaScript, modificando a variável responsável por sua posição horizontal.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou abrir issues para melhorias ou correções.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
