# Dicionário do Eufemismo — Terra Mãe

Jogo de associação interativo, feito para acompanhar o Círculo de Leitura sobre o livro *Lua de Larvas*, de Sally Gardner. O aluno associa cada expressão da propaganda da Terra Mãe (cartas vermelhas) à realidade que ela esconde (cartas cinzas).

Arquivo único, sem dependências externas além de uma fonte do Google Fonts. Funciona em qualquer navegador, celular ou computador.

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (por exemplo, `dicionario-eufemismo`).
2. Envie o arquivo `index.html` **e a pasta `assets`** (com as 15 imagens) para a raiz do repositório, mantendo essa estrutura de pastas. Pelo botão "Add file" > "Upload files", você pode arrastar o arquivo e a pasta juntos.
3. No repositório, vá em **Settings** > **Pages**.
4. Em "Source", selecione a branch `main` e a pasta `/ (root)`. Clique em **Save**.
5. Aguarde alguns minutos. O link do jogo aparecerá na própria página de Pages, no formato:
   `https://SEU-USUARIO.github.io/dicionario-eufemismo/`
6. Esse link pode ser compartilhado direto com os alunos ou incorporado numa página do Google Sites, usando o bloco "Incorporar" > "Por URL".

## Recursos de acessibilidade já incluídos

- Sem cronômetro e sem pontuação exibida durante o jogo, apenas ao final.
- Botão de áudio (🔊) em cada carta, que lê o texto em voz alta usando a leitura de tela nativa do navegador.
- Cores fortes e ícones para diferenciar os dois conjuntos de cartas, além do texto (não depende só da cor).
- Contraste alto, fonte legível (Lexend) e alvos de toque grandes.
- Feedback visual e sonoro claro tanto no acerto quanto no erro, sem punição além de tentar de novo.
- Resumo final com classificação (Ótimo / Médio / Precisa de mais atenção) para orientar a releitura.

## Personalizar o conteúdo

Os 15 pares estão no início do bloco `<script>`, no array `pairs`. Basta editar `term` (a fala da Terra Mãe) e `reality` (o que está escondido) para ajustar ou ampliar o glossário.
