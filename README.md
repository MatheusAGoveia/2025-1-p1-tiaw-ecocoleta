# EcoColeta
CURSO: Sistema de informção
DISCIPLINA : Trabalho Interdiciplinar Aplicação Web 
1° semestre/2025

EcoColeta é um sistema voltado para otimizar a coleta seletiva e promover a sustentabilidade nas cidades. A plataforma incentiva a conscientização ambiental por meio de uma interface acessível que conecta cidadãos, agentes de coleta e pontos de descarte. Com uma abordagem educativa e prática, o sistema fortalece hábitos sustentáveis e a participação ativa da comunidade na gestão de resíduos.

O sistema conta com um dashboard administrativo integrado, que oferece uma visão estratégica das coletas realizadas, rotas otimizadas, tipos de resíduos e engajamento dos usuários. Isso facilita o controle por parte de cooperativas, órgãos públicos ou administradores locais, tornando o processo mais eficiente, transparente e ecológico.
#Integrantes
Matheus Augusto Alves Goveia Damião
Samuel Maciel da Silva Figueiredo
Kauan Gomes Marques
Ronaldo Augusto Oliveira Lacerda
Artur Ferreira Silva
#Professora
Amália Soares Vieira de Vasconcelos

## 🚀 Funcionalidades

- **Dashboard Administrativo**: Visualização completa de dados, estatísticas e gráficos
- **Sistema de Usuários**: Cadastro e autenticação de doadores e coletores
- **Pontos de Coleta**: Gestão e localização de pontos de coleta
- **Comunidades**: Sistema de comunidades para engajamento
- **API Integrada**: JSON Server integrado para desenvolvimento
- **Interface Responsiva**: Funciona em desktop e mobile

## 📋 Requisitos

- Node.js (versão 14 ou superior)
- npm (gerenciador de pacotes do Node.js)

## ⚡ Instalação e Execução Rápida

### Método 1: Script Automático (Recomendado)
1. Execute o arquivo `start-dashboard.bat`
2. Aguarde a instalação automática das dependências
3. O dashboard será aberto automaticamente no navegador

### Método 2: Comandos Manuais
1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/ecocoleta.git
cd ecocoleta/EcoColetaPrograma/ecoColeta-Presentation
```

2. Instale as dependências:
```bash
npm install
```

3. Inicie a aplicação:
```bash
npm start
```

## 🌐 URLs Disponíveis

Após iniciar com `npm start`, acesse:

- **🏠 Página Principal**:https://two025-1-p1-tiaw-ecocoleta.onrender.com/index.html
- **📊 Dashboard Admin**: http://two025-1-p1-tiaw-ecocoleta.onrender.com/dashboardAdmin.html
- **👤 Autenticação**: http://two025-1-p1-tiaw-ecocoleta.onrender.com/autent.html
- **👥 Comunidades**: http://two025-1-p1-tiaw-ecocoleta.onrender.com/comunidade.html
- **⚙️ Teste da API**: http://two025-1-p1-tiaw-ecocoleta.onrender.com/test-api.html

## 📡 API Endpoints

A aplicação roda com JSON Server integrado:

- **Base URL**: http:/two025-1-p1-tiaw-ecocoleta.onrender.com/api
- **Usuários**: `/api/usuarios`
- **Pontos de Coleta**: `/api/pontosDeColeta`
- **Comunidades**: `/api/comunidades`
- **Doações**: `/api/donations`
- **Agendamentos**: `/api/agendamentos`

## Estrutura do Projeto

```

├── src/
│   ├── css/
│   │   ├── doacoes.css
│   │   └── navFooter.css
│   ├── js/
│   │   ├── doacoes.js
│   │   ├── doacao-realizada.js
│   │   └── navFooter.js
│   └── pages/
│       ├── doacoes.html
│       ├── doacao-realizada.html
│       └── home.html
├── db.json
├── package.json
└── README.md
```

## Funcionalidades

- Sistema de doações com valores predefinidos
- Formulário de doação com validação
- Integração com API de pagamento (mock)
- Armazenamento de doações no JSON Server
- Página de confirmação de doação
- Design responsivo
- Animações e transições suaves

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)
- JSON Server (mock backend)
- Font Awesome (ícones)

## Contribuição

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
