# Ψ — Perfume e Sabor do Eu

Página do quadro. A animação de Fourier desenha a letra; o modo
"ver sobre o quadro" encaixa a animação em cima do quadro impresso.

## Publicar

1. Crie um repositório chamado **`PSI`** — em MAIÚSCULAS.
   O QR do quadro aponta para `https://psgoncalvesjr-ghai.github.io/PSI/` e o caminho depois da barra
   diferencia maiúsculas de minúsculas.

2. Suba o conteúdo desta pasta na raiz do repositório.

3. Em Settings → Pages, escolha a branch `main` e a pasta `/ (root)`.

4. Espere uns minutos e abra https://psgoncalvesjr-ghai.github.io/PSI/

## Fazer o "ver sobre o quadro" funcionar

O reconhecimento precisa de um arquivo compilado a partir da imagem do quadro.
Ele não pode ser gerado aqui porque a ferramenta roda no navegador.

1. Abra https://hiukim.github.io/mind-ar-js-doc/tools/compile
2. Envie o arquivo `alvo.jpg` desta pasta.
3. Clique em *Start* e depois em *Download*.
4. Renomeie o arquivo baixado para **`alvo.mind`** e coloque nesta pasta.
5. Suba de novo.

Sem esse arquivo a página funciona normalmente — só o botão
"ver sobre o quadro" é que não encontra o alvo.

## Detalhes

- A animação usa 1441 vetores girantes (K = 720), os mesmos do quadro impresso.
- A letra vem da curva exata do glifo Ψ do Times New Roman, não de uma imagem.
- A página é um arquivo só e funciona sem internet depois de carregada,
  exceto o modo câmera, que busca duas bibliotecas externas.
