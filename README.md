# Transcrição de Áudio

Uma aplicação web moderna para transcrição de áudio em texto usando a API AssemblyAI e Gemini API

## Funcionalidades

-  Upload de arquivos de áudio por drag-and-drop
-  Transcrição de áudio para texto em português
-  Barra de progresso em tempo real
-  Copiar texto para área de transferência
-  Download da transcrição em formato texto
-  Suporte para formatos MP3, WAV, M4A e MP4
-  Estatísticas de palavras e duração

## Tecnologias Utilizadas

- Next.js 14
- React
- TypeScript
- Tailwind CSS
- AssemblyAI API
- React Dropzone
- Sonner (Toasts)

## Como Executar

1. Clone o repositório:
```bash
git clone (https://github.com/Keymiuz/WordPressa.git)
cd https://github.com/Keymiuz/WordPressa.git)
```

2. Instale as dependências:
```bash
cd my-app
npm install
```

3. Configure as variáveis de ambiente:
Crie um arquivo `.env.local` na raiz do projeto e adicione:
```
ASSEMBLYAI_API_KEY=sua_chave_api
```

4. Inicie o servidor de desenvolvimento:
```bash
npm run dev
```

5. Abra [http://localhost:3000](http://localhost:3000) no seu navegador.

## Estrutura do Projeto

```
my-app/
├── app/
│   ├── api/
│   │   └── transcribe/
│   │       └── route.ts    # API de transcrição
│   └── page.tsx            # Página principal
├── components/
│   └── FileUpload.tsx      # Componente de upload
└── public/
```

## Uso da API

A aplicação utiliza a API AssemblyAI para transcrição de áudio. O processo inclui:

1. Upload do arquivo de áudio
2. Processamento e transcrição
3. Retorno do texto transcrito com metadados

## Limitações

- Tamanho máximo de arquivo: 25MB
- Formatos suportados: MP3, WAV, M4A, MP4
- Idioma: Português (Brasil)
- Tempo máximo de processamento: 30 segundos

## Contribuindo

Sinta-se à vontade para contribuir com o projeto. Abra uma issue ou envie um pull request.


