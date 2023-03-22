# Library vlibras react

customization and update in the code

## Esse componente segue os padrões fornecidos na documentação do vlibras.

* Os surdos enfrentam bastante dificuldade para ler, escrever e se comunicar na língua oral do seu país. Dessa forma, para tentar reduzir esses problemas, o objetivo da ferramenta computacional de código aberto, denominada VLibras Widget, consiste em traduzir conteúdos do Português Brasileiro para a Língua Brasileira de Sinais (LIBRAS), tornando websites acessíveis a pessoas surdas.

### Instalação:
npm install -S @djpfs/react-vlibras


### Como usar:

React App

<img alt='imgtutorial' src='https://github.com/djpfs/react-vlibras/raw/main/public/assets/react.png'>

**Parametros**

Você pode usar a propriedade `forceOnload` para forçar que o VLibras seja carregado a partir de decisões assíncronas, ja que por padrão ele é executado no evento `onload`.

```typescript
import VLibras from './index'

function App() {
  return (
    <div className="App">
      <VLibras forceOnload={true} />
      <header className="App-header">
        <h1>Teste</h1>
      </header>
    </div>
  )
}

export default App
```

### Resultado:

<img alt='imgresutado' src='https://github.com/djpfs/react-vlibras/raw/main/public/assets/result2.png'>


credits: user git (djpfs)



