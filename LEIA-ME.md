# Psi — Perfume e Sabor do Eu

Pagina do quadro. A animacao de Fourier desenha a letra; o modo
"ver sobre o quadro" encaixa a animacao em cima do quadro impresso.

## Arquivos

    index.html                        a pagina
    alvo.jpg                          imagem para compilar o reconhecimento
    alvo.mind                         (voce gera — veja abaixo)
    three.module.js                   biblioteca 3D
    mindar-image-three.prod.js        reconhecimento de imagem
    controller-mGt1s8dJ.js            (carregado pelo anterior)
    ui-fBadYuor.js                    (carregado pelo anterior)
    jsm/renderers/CSS3DRenderer.js    (carregado pelo anterior)

As bibliotecas ficam AQUI, nao em servidor de terceiros. Se o serviço que
as distribui sair do ar daqui a alguns anos, o quadro continua funcionando.

## Publicar

1. Suba tudo na raiz do repositorio `PSI` (o QR do quadro aponta para
   https://psgoncalvesjr-ghai.github.io/PSI/, e o caminho depois da barra diferencia maiusculas).
2. Settings -> Pages -> branch `main`, pasta `/ (root)`.
3. Abra https://psgoncalvesjr-ghai.github.io/PSI/

## Gerar o reconhecimento (alvo.mind)

A ferramenta roda no navegador e nao pode ser executada fora dele.

1. Abra https://hiukim.github.io/mind-ar-js-doc/tools/compile
2. Envie o `alvo.jpg` desta pasta.
3. *Start*, espere de 1 a 3 minutos, e *Download*.
4. Renomeie o arquivo baixado para **`alvo.mind`** e suba aqui.

Sem esse arquivo a pagina funciona normalmente — so o botao
"ver sobre o quadro" avisa que o reconhecimento ainda nao foi publicado.

## Detalhes

- A animacao usa 1441 vetores girantes (K = 720), os mesmos do quadro.
- A letra vem da curva exata do glifo Psi do Times New Roman, nao de imagem.
- A animacao em tela funciona sem internet depois de carregada.
