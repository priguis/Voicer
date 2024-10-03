# Voicer
página web que permite gravação de voz, transcrição com IA generativa e envio do conteúdo para plataformas como Notion, Google Docs e Evernote

voice-transcription-app/
│
├── public/               # Arquivos estáticos acessíveis pelo navegador
│   ├── css/              # Estilos CSS
│   │   └── styles.css    # Estilos da interface
│   ├── js/               # Scripts JavaScript do frontend
│   │   └── app.js        # Lógica da gravação e transcrição de voz
│   └── index.html        # Página HTML principal
│
├── src/                  # Código fonte do backend
│   ├── routes/           # Rotas da API
│   │   ├── googleDocs.js # Rota para enviar transcrição para Google Docs
│   │   ├── evernote.js   # Rota para enviar transcrição para Evernote
│   │   └── notion.js     # Rota para enviar transcrição para Notion
│   ├── services/         # Serviços de integração com APIs externas
│   │   ├── openai.js     # Serviço de integração com IA generativa (OpenAI)
│   │   ├── notionService.js  # Serviço de integração com Notion API
│   │   ├── googleDocsService.js # Serviço de integração com Google Docs API
│   │   └── evernoteService.js  # Serviço de integração com Evernote API
│   ├── config/           # Configurações gerais da aplicação
│   │   └── apiKeys.js    # Chaves de API e outras configurações sensíveis
│   ├── app.js            # Configuração do servidor Express e middlewares
│   └── server.js         # Inicialização do servidor
│
├── .env                  # Variáveis de ambiente (chaves de API, credenciais)
├── package.json          # Dependências do Node.js e scripts de execução
├── README.md             # Documentação do projeto
└── LICENSE               # Licença do projeto
