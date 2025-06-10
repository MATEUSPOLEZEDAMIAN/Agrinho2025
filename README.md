Agrinho 2025 - Conexão Campo Cidade
Este é o repositório do site do evento "Agrinho 2025", que celebra e fortalece a conexão vital entre o campo e a cidade. O site foi desenvolvido para informar os visitantes sobre o evento, suas áreas temáticas, destaques e como participar.

Visão Geral
O site "Agrinho 2025" foi concebido para ser uma plataforma informativa, destacando a importância da integração entre o ambiente rural e urbano para o desenvolvimento sustentável. Ele apresenta uma interface moderna e responsiva, utilizando o framework Bootstrap 5 para garantir uma experiência de usuário consistente em diferentes dispositivos.

Funcionalidades e Seções Principais
O site é dividido em seções claras, permitindo que os usuários naveguem facilmente pelas informações do evento:

Cabeçalho (<header>): Apresenta o título principal do evento "AGRINHO 2025" e o subtítulo "Festejando Conexão Campo Cidade", com uma breve descrição. As fontes utilizadas são 'Oswald' para o título principal e 'Roboto Slab' para o subtítulo, conferindo um estilo visual distinto.
Barra de Navegação (<nav>): Uma barra de navegação superior fixa (sticky-top) com fundo verde (bg-success) que inclui links para as principais seções do site:
Página Inicial (index.html)
Energia Rural (energia.html)
Acessibilidade a Água (agua.html)
Produção (producao.html)
Inscrições (inscricoes.html)
Contato (contato.html) Os links possuem um estilo de destaque (font-weight: 500) e um efeito sutil de transição de cor ao passar o mouse.
Seção "A Importância da Conexão Campo-Cidade": Uma seção de destaque na página inicial que discorre sobre a relevância da integração entre o campo e a cidade, acompanhada de uma imagem ilustrativa. O texto sublinha a troca de vidas, histórias e cuidados entre os dois ambientes.
"Explore as Áreas Temáticas": Apresenta as três principais áreas temáticas do evento através de cards interativos, cada um com uma imagem, título, breve descrição e um botão "Saiba mais" que direciona para páginas específicas:
Acessibilidade e Sustentabilidade da Água
Energia Rural e Fontes Renováveis
Produção, Industrialização e Inovação no Campo Os cards possuem sombras e as imagens (.img-card) têm um efeito de leve ampliação (transform: scale(1.05)) ao passar o mouse.
"Destaques do Evento": Um carrossel de imagens (.carousel slide) que destaca os principais atrativos do Agrinho 2025:
Feira de Tecnologia e Inovação
Palestras com Autoridades e Especialistas
Premiações a Alunos e Professores As legendas do carrossel têm sombra no texto (text-shadow) para melhorar a legibilidade sobre as imagens.
Seção de Inscrição: Uma chamada para ação convidando os visitantes a se inscreverem no evento, com um botão "Inscrever-se" que leva à página de inscrição.
Rodapé (<footer>): Contém informações de direitos autorais, o realizador do site (Mateus Poleze Damian) e um link para a página de contato.
Design e Estilo (CSS)
O site utiliza um arquivo style.css personalizado para complementar o Bootstrap e adicionar um toque único:

Fontes Personalizadas: Importa as fontes 'Oswald' e 'Roboto Slab' do Google Fonts para uso nos títulos e elementos específicos (.font-oswald, .font-roboto-slab).
Imagens: Estilos para imagens de diferentes seções (.img-agro, .img-card, .img-slide) garantem responsividade, bordas arredondadas e sombras para um visual mais agradável. O efeito de hover nas imagens dos cards (.img-card:hover) adiciona interatividade.
Componentes Bootstrap Customizados: Ajustes em componentes como .cabecalho h3 (cor de aviso do Bootstrap), .navbar-nav .nav-link (destaque e transição de cor), .card (sombras) e .btn-outline-* (destaque no peso da fonte).
Efeito de Transição de Página: Um CSS e JavaScript customizados (body, .page-transition-overlay) criam um efeito de "carregando" (Carregando...) e transição suave (fade-in/fade-out) ao carregar a página e ao navegar entre as seções, melhorando a experiência do usuário.
Tecnologias Utilizadas
HTML5: Estrutura fundamental do site.
CSS3: Estilização e design.
JavaScript: Para funcionalidades interativas, como o carrossel do Bootstrap e as transições de página.
Bootstrap 5.3.5: Framework CSS para design responsivo e componentes pré-estilizados.
Google Fonts: Para as fontes 'Oswald' e 'Roboto Slab'.
Acesso ao Site
Você pode visitar o site do Agrinho 2025 através do seguinte link: https://agrinho2025-cnfe.vercel.app/
