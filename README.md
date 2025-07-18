Dashboard Financeiro - Projeto Léo Santana
Este repositório contém o código-fonte de um dashboard financeiro interativo, desenvolvido em React, para o acompanhamento detalhado dos custos de lançamento e operação da plataforma de conteúdo do Léo Santana.

🚀 Visão Geral do Projeto
O objetivo deste dashboard é fornecer uma ferramenta visual e detalhada para a gestão financeira do projeto de transmissão interativa do Léo Santana. Ele permite visualizar:

Custos Iniciais (CAPEX): Investimentos em desenvolvimento de plataforma, equipamentos e estruturação legal.

Custos Operacionais Mensais (OPEX): Despesas recorrentes com equipe, infraestrutura digital, marketing e administração.

Custos Variáveis: Despesas específicas para eventos de grande porte, como a transmissão do Carnaval.

Roadmap de Desembolso: Projeção gráfica dos aportes financeiros mês a mês, com valores parciais e acumulados.

Dashboards Detalhados: Gráficos específicos para análise de custos por categoria (equipe, plataforma, equipamentos, carnaval, marketing, infraestrutura, administrativo, legal).

✨ Funcionalidades Principais
Visão Geral Financeira: Cards de resumo com os principais indicadores de custo (CAPEX, OPEX mensal, custo Carnaval, custo total 1º ano).

Projeção de Desembolso: Gráfico combinado de barras e linha mostrando custos mensais e acumulados ao longo de 12 meses.

Tabelas Detalhadas: Abas dedicadas para detalhar CAPEX, OPEX e custos do Carnaval, com descrições e valores.

Roadmap de Gantt Simplificado: Visualização das fases do projeto e profissionais envolvidos (com tooltip ao passar o mouse).

Dashboards por Categoria: Gráficos de área empilhada e de linha para analisar a evolução dos custos por tipo (equipe, plataforma, equipamentos, etc.).

Interface Intuitiva: Navegação por abas para fácil acesso às diferentes seções do relatório financeiro.

🛠️ Tecnologias Utilizadas
Frontend: React.js

Visualização de Dados: Recharts

Estilização: Tailwind CSS

Gerenciamento de Pacotes: npm / Yarn

📦 Como Rodar o Projeto Localmente
Para configurar e rodar o dashboard em seu ambiente de desenvolvimento:

Clone o repositório:

git clone https://github.com/SeuUsuario/seu-repositorio.git
cd seu-repositorio

(Lembre-se de substituir SeuUsuario e seu-repositorio pelo seu usuário e nome do repositório no GitHub.)

Instale as dependências:

npm install
# ou
yarn install

Inicie o servidor de desenvolvimento:

npm start
# ou
yarn start

A aplicação será aberta automaticamente no seu navegador em http://localhost:3000.

🚀 Implantação (Deployment)
Para implantar esta aplicação em um ambiente de produção (ex: Hostinger):

Construa a aplicação para produção:

npm run build
# ou
yarn build

Isso criará uma pasta build/ na raiz do projeto, contendo os arquivos otimizados para produção.

Faça o upload dos arquivos: O conteúdo da pasta build/ deve ser carregado para a pasta public_html do seu servidor de hospedagem.

Configure o .htaccess: Para Single Page Applications (SPAs) como esta, é crucial configurar um arquivo .htaccess na raiz do seu public_html para que o roteamento interno do React funcione corretamente. O conteúdo necessário é:

<IfModule mod_rewrite.c>
  RewriteEngine On
  RewriteBase /
  RewriteRule ^index\.html$ - [L]
  RewriteCond %{REQUEST_FILENAME} !-f
  RewriteCond %{REQUEST_FILENAME} !-d
  RewriteCond %{REQUEST_FILENAME} !-l
  RewriteRule . /index.html [L]
</IfModule>

Consulte a documentação do seu provedor de hospedagem para detalhes sobre como criar ou editar arquivos .htaccess.

🤝 Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues para sugestões ou bugs, ou enviar pull requests com melhorias.

📧 Contato
Para dúvidas ou suporte, entre em contato com [Seu Nome/Email/Link de Contato].
