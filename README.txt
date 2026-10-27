Site do Colégio Manacá — arquivos para edição local
=====================================================

Estrutura da pasta:
  index.html   -> estrutura e conteúdo (texto) do site
  style.css    -> todo o visual (cores, fontes, espaçamentos, responsividade)
  imagens/     -> logo e fotos usadas no site, com nomes descritivos:
       logo-colegio-manaca.png  -> logotipo oficial
       fachada.jpg              -> simulação da fachada (hero)
       sala-de-aula.jpg         -> simulação de sala de aula
       corredor.jpg             -> simulação do corredor de acesso às salas
       recepcao.jpg             -> simulação da recepção / secretaria / direção
       biblioteca.jpg           -> simulação do cantinho de leitura da biblioteca
       quadra.jpg               -> simulação da quadra poliesportiva

Como abrir:
  Basta dar duplo clique em "index.html" — ele abre em qualquer navegador
  (Chrome, Firefox, Edge etc.), sem precisar instalar nada nem rodar servidor.
  É necessário estar conectado à internet apenas para carregar as fontes
  (Fraunces e Nunito, vindas do Google Fonts) — o resto do site funciona
  offline normalmente.

Como editar:
  - Textos, títulos e estrutura das seções: edite o index.html com qualquer
    editor de texto (recomendo o VS Code, é gratuito).
  - Cores, tamanhos de fonte, espaçamentos, layout responsivo: edite o
    style.css. As cores principais do site estão centralizadas no topo do
    arquivo, dentro de ":root { ... }" (ex: --brand-deep é o verde escuro
    do cabeçalho e rodapé).
  - Trocar uma foto: substitua o arquivo correspondente dentro de
    "imagens/" mantendo o mesmo nome, ou troque o nome do arquivo e ajuste
    a referência dentro do index.html (procure por <img src="imagens/...").

Qualquer alteração, é só salvar o arquivo e atualizar a página no navegador
para ver o resultado.
