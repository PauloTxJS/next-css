# Next.js + CSS global

### 1º Crie um arquivo no diretório 'pages' chamado '_app.js' e cole o seguinte código:

import '../styles.css'

// This default export is required in a new `pages/_app.js` file.
export default function MyApp({ Component, pageProps }) {
  return <Component {...pageProps} />
}

### 2º Salve o arquivo e, na raiz do projeto crie um arquivo chamado 'styles.css'.
Todo o 'CSS' da sua aplicação ficará no arquivo 'styles.css' e o mesmo só deverá ser importado no arquivo 'pages/_app.js' para evitar conflitos.

