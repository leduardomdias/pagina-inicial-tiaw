# FindPet - Páginas WebSite

## Descrição

**FindPet** é um projeto focado em ajudar pessoas a encontrarem seus animais desaparecidos com mais facilidade. O objetivo principal deste portal é conectar donos de pets com pessoas que possam ter encontrado animais perdidos.

Esta página inicial oferece uma introdução ao site, onde o usuário pode navegar pelas regiões, pesquisar por animais desaparecidos, cadastrar seu pet e explorar novos recursos como a exposição de produtos.

## Funcionalidades

- **Menu de Navegação**: Inclui links para as seções principais, como _Home_, _Sobre_, _Fórum_, _Meus Pets_.
- **Carrossel de Regiões**: Exibe imagens e descrições de regiões sugeridas para facilitar a busca de animais desaparecidos.
- **Menu de Regiões**: Uma barra lateral com links rápidos para diferentes regiões da cidade.
- **Cadastro de Pets**: Redireciona à página de cadastro para adicionar informações sobre pets desaparecidos.
- **Busca de Animais**: Campo de pesquisa para encontrar animais no banco de dados.
- **Exposição de Produtos**: Espaço dedicado à venda de produtos relacionados a pets.
- **Página de Regiões**: Navegação fácil para páginas específicas de regiões, acessada por botão destacado.
- **Páginas de Cadastro**: Para registrar informações de cães e gatos desaparecidos.
- **Página de Login e Cadastro de Usuários**: Para acessar e gerenciar informações de animais cadastrados.
- **Modelo de Panfleto**: Página para baixar um modelo de panfleto personalizado para divulgar pets desaparecidos.
- **Exibição de Animais Cadastrados**: Página que apresenta todos os animais cadastrados, permitindo visualização e exclusão de registros.
- **Suporte para Imagem por URL**: Opção para cadastrar pets utilizando imagens através de URL, além do upload de arquivos.
- **Página de Panfleto**: Seção para baixar um panfleto pré-pronto para impressão, ajudando na divulgação da busca pelo pet perdido.
- **Frase Motivacional**: Adicionada uma frase de consolo abaixo do modelo de panfleto, incentivando o usuário na busca pelo seu pet.

## Páginas Disponíveis

- `index.html`: Página inicial do projeto.
- `regioes.html`: Lista regiões para facilitar a busca por pets desaparecidos.
- `login.html`: Página de login para usuários registrados.
- `cadastro.html`: Página de cadastro de novos usuários.
- `cadastrarPet.html`: Formulário para cadastrar animais desaparecidos.
- `pets.html`: Página que mostra todos os pets cadastrados.
- `perfilDoUsuario.html`: Página com as informações do perfil do usuário e seus pets cadastrados.
- `pageProdutos.html`: Página dos produtos do site.
- `panfleto.html`: Página para baixar um modelo de panfleto para divulgar pets desaparecidos.

## Tecnologias Utilizadas

- **HTML5**: Estruturação da página.
- **CSS3** (via Bootstrap): Estilização responsiva e design moderno.
- **Bootstrap 5**: Framework CSS para design responsivo.
- **JavaScript**: (Previsto para uso em funcionalidades dinâmicas futuras).

## Como Usar

Prepare-se para a jornada de encontrar seu pet! Aqui está o passo a passo:

1. Clone o Repositório: Entre na missão e traga o projeto para sua máquina local!

```bash
git clone https://github.com/leduardomdias/pagina-inicial-tiaw.git
```
2.  Navegue até o Diretório: Avance até o seu novo tesouro digital.

```bash
cd pagina-inicial-tiaw
```
3. Instale o JSON Server: Se ainda não tiver, é hora de equipar-se!

```bash
npm install -g json-server
```
4.  Crie um Arquivo db.json: Monte seu banco de dados de animais! Aqui está um exemplo para começar:

```bash
{
  "animais": [
    {
      "id": 1,
      "nome": "Rex",
      "tipo": "Cachorro",
      "idade": "2 anos",
      "descricao": "Cachorro amigável.",
      "imagem": "rex.png",
      "regiao": "Buritis"
    },
    {
      "id": 2,
      "nome": "Mia",
      "tipo": "Gato",
      "idade": "1 ano",
      "descricao": "Gato curioso.",
      "imagem": "mia.png",
      "regiao": "Funcionários"
    }
  ]
}
```

5. Inicie o JSON Server: Dê vida ao seu servidor

```bash
json-server --watch db.json
```

6. Abra o index.html: E voilà! Acesse seu site e comece a busca por pets desaparecidos!

```bash
Sinta-se à vontade para ajustar qualquer parte ou adicionar mais informações conforme necessário!
```
