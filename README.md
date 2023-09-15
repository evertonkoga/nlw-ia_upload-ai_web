<center>
  <p align="center">
    <img src="https://github.com/evertonkoga/nlw-ia_upload-ai_web/assets/54872138/950fc77b-96c0-47dd-9a43-77c0f49584c2" width=110px height="110px" /> &nbsp;
    <img src="https://github.com/evertonkoga/nlw-ia_upload-ai_web/assets/54872138/b59b733d-1fa7-4b2a-b741-58647bfa48e7" width=110px height="110px" /> &nbsp;
    <img src="https://github.com/evertonkoga/nlw-ia_upload-ai_web/assets/54872138/281df55f-69a7-4322-9e93-e50df1a48eb5" width=110px height="110px"/>
  </p>  
  <h1 align="center">🎬 Front-end: Gerador de conteúdo com IA através de vídeos</h1>
  <p align="justify">    
    O front-end recebe o envio de um vídeo, extrai seu conteúdo de áudio e, em seguida, envia uma solicitação ao back-end para a transcrição, juntamente com uma ou mais palavras-chave.
    Posteriormente, solicita ao back-end a geração de um conteúdo dinâmico com base em prompts previamente cadastrados em um banco de dados.<br/>
    Para desenvolver o front-end, foi utilizado o <b><a href="https://vitejs.dev/">Vite</a></b> com as tecnologias <b>React, <a href="https://tailwindcss.com/">Tailwind CSS</a>, <a href="https://ui.shadcn.com/">shadcn/ui</a></b> e <b><a href="https://www.radix-ui.com/">Radix UI</a></b>,
    com o suporte da biblioteca <b><a href="https://ffmpegwasm.netlify.app/docs/overview">ffmpeg</a></b> para a manipulação e conversão de vídeo em áudio, diretamente no navegador utilizando o <b>WebAssembly</b>.
    Além disso, foi aprimorado essa funcionalidade incorporando a biblioteca <b>ai</b>, que permite a exibição em tempo real do conteúdo retornado pelo back-end em um fluxo contínuo, apresentando gradativamente os conteúdos ao usuário.
  </p>
</center>
<br />

## Como executar?

1. Clonar o repositório:
```sh
git clone https://github.com/evertonkoga/nlw-ia_upload-ai_web.git
```

2. Baixar as dependências:
```shell
yarn
```

3. Executar o projeto:
```shell
yarn dev
```
