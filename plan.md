# Plano de implementação — Yasmim / Portfólio Administrativo

## Direção visual
- **Movimento:** editorial digital elegante, com influência de design suíço e interfaces de laboratório de tecnologia.
- **Princípios:** contraste controlado, ritmo vertical generoso, informação em camadas e detalhes precisos.
- **Filosofia de cor:** fundo azul-noite quase preto para transmitir foco; branco mineral para leitura; verde menta elétrico como assinatura de inovação; âmbar pontual para sinalizar descoberta.
- **Layout:** composição assimétrica em trilha editorial, com hero dividido entre narrativa e cartão visual; blocos de conteúdo em painéis e uma linha de progresso vertical.
- **Elementos assinatura:** etiqueta de seção monoespaciada, marcador circular de progresso e textura de pontos/grade técnica.
- **Interação:** movimentos discretos e respostas rápidas, reforçando a ideia de precisão administrativa aplicada à inovação.
- **Animação:** entrada por fade + deslocamento curto, hover com elevação mínima, parallax suave no cartão hero e barra de leitura atualizada via JavaScript.
- **Tipografia:** `Inter`/system para leitura e `Space Mono`/monospace para metadados, números e etiquetas. Sem dependências externas.
- **Essência da marca:** Yasmim traduz organização, curiosidade e visão de futuro em experiências administrativas que conectam pessoas e tecnologia.
- **Voz:** segura, objetiva e curiosa. Exemplos: “Organização também é uma forma de inovação.” / “Ideias complexas, caminhos mais claros.”
- **Wordmark:** monograma “Y.” em círculo técnico, acompanhado do nome em caixa alta espaçada.
- **Cor proprietária:** verde menta `#9DF3D8`.

## Implementação
- Site estático em HTML5 semântico, CSS3 e JavaScript puro, servido por `server.py` sem dependências externas.
- `index.html` concentra a estrutura single-page e mantém os caminhos de mídia solicitados literalmente substituíveis.
- `styles.css` concentra tokens, responsividade, estados de hover, animações e fallback visual das mídias.
- `script.js` cuida de menu mobile, IntersectionObserver, progresso de leitura, ano automático e microinterações.
- `manus-routes.json` declara a rota `/` para a infraestrutura de Preview.
- Pastas `imagens/`, `video/`, `audio/`, `animacao/` e `musica/` ficam prontas para receber os arquivos finais.

## Estrutura
- `/index.html`: página e conteúdo editorial.
- `/styles.css`: sistema visual responsivo.
- `/script.js`: interações sem framework.
- `/server.py`: servidor local de Preview na porta 3000.
- `/manus-routes.json`: manifesto de rotas.
- `/imagens`, `/video`, `/audio`, `/animacao`, `/musica`: pontos de substituição de mídia.
