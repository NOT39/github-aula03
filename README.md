
# Título do Projeto

Uma breve descrição sobre o que esse projeto faz e para quem ele é


## Documentação da API

#### Retorna todos os itens

```http
  GET /api/items
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `api_key` | `string` | **Obrigatório**. A chave da sua API |

#### Retorna um item

```http
  GET /api/items/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. O ID do item que você quer |

#### add(num1, num2)

Recebe dois números e retorna a sua soma.


## Autores

- [@octokatherine](https://www.github.com/octokatherine)


## Demonstração

Insira um gif ou um link de alguma demonstração


## Instalação

Instale my-project com npm

```bash
  npm install my-project
  cd my-project
```
    
## Aprendizados

O que você aprendeu construindo esse projeto? Quais desafios você enfrentou e como você superou-os?


![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)


## Rodando localmente

Clone o projeto

```bash
  git clone https://link-para-o-projeto
```

Entre no diretório do projeto

```bash
  cd my-project
```

Instale as dependências

```bash
  npm install
```

Inicie o servidor

```bash
  npm run start
```


## Stack utilizada

**Front-end:** React, Redux, TailwindCSS

**Back-end:** Node, Express


## Uso/Exemplos

```javascript
import Component from 'my-project'

function App() {
  return <Component />
}
```

