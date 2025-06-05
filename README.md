<h1 align="center">Portifólio Origamid (com alguns extras)</h1>

<p align="center">Projeto feito com o intuito de mimetizar o Portifólio mostrado nos cursos da Origamid.</p>

<hr />

## Pré-requisitos

- Node.js
- npm

### Comandos

| Comando         | O que faz?                  | Observação                     |
| --------------- | --------------------------- | ------------------------------ |
| `npm install`   | Instala pacotes necessários | **Execute isso primeiro!**     |
| `npm start`     | Inicia o desenvolvimento    | Acesse `http://localhost:1234` |
| `npm run build` | Faz build do site           | Resultado na pasta `dist`      |

## Considerações

É preciso executar `npm start` e começar a mexer no projeto _como se não houvesse amanhã_.
Parcel oferece _hot reload_: conforme alterações de código são feitas, ele faz rebuild automático dos arquivos alterados e atualiza o navegador.

O arquivo `style/index.scss` carrega todos os demais (partials), então, sempre que criar um novo arquivo na estrutura, lembre-se de importá-lo -- dentro dos conceitos da arquitetura ITCSS.
