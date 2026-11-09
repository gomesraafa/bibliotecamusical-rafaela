# 🎵 Sistema Musical

## Sobre o projeto

O Sistema Musical foi desenvolvido como atividade das aulas de desenvolvimento web. A ideia do projeto é criar um site onde seja possível organizar artistas e músicas de forma simples e prática.

O sistema conta com páginas de login, biblioteca musical, cadastro de artistas e cadastro de músicas. Cada página possui suas próprias funções, mas todas seguem o mesmo estilo visual.

## Tecnologias utilizadas

Durante o desenvolvimento, utilizamos:

- **HTML5:** para criar a estrutura das páginas e os formulários.
- **CSS3:** para personalizar as cores, fontes, botões, tabelas e o visual do site.
- **Visual Studio Code:** para escrever e organizar os códigos.

## Como o sistema funciona

O projeto possui algumas páginas principais:

### Login

É a primeira tela do sistema. Nela, o usuário pode digitar seu nome de usuário e senha para entrar.

Credenciais de teste:
- Usuário: `admin`
- Senha: `123`

### Biblioteca Musical

Nessa página ficam as músicas cadastradas. É possível visualizar informações como título, artista, álbum e gênero musical.

Também foram adicionados filtros para facilitar a busca por músicas e botões para acessar o YouTube, editar ou excluir registros.

### Cadastro de Artistas

Essa página permite preencher as informações dos artistas, como nome, gênero musical, país e foto.

Abaixo do formulário, existe uma tabela para visualizar os artistas cadastrados, com opções de edição, exclusão e acesso às músicas de cada artista.

### Cadastro de Músicas

Nessa parte é possível preencher os dados de uma música, informando o artista, título, álbum, gênero, link do YouTube, capa e letra da música.

Também existe uma tabela que mostra as músicas cadastradas.

## Arquivo CSS

Para manter todas as páginas com o mesmo visual, utilizamos um único arquivo chamado `styles.css`.

Nele estão definidos os estilos dos formulários, botões, tabelas, títulos, cores, espaçamentos e outros elementos do sistema.

Também foram utilizadas variáveis CSS para facilitar a organização das cores e manter a padronização das páginas.

Além disso, o CSS possui ajustes para que o site consiga se adaptar a telas menores, como celulares e tablets.

## Organização dos arquivos

Os arquivos do projeto estão organizados da seguinte maneira:

```text
Sistema-Musical/
│
├── index.html
├── biblioteca.html
├── cadastro_artista.html
├── cadastro_musica.html
├── styles.css
│
└── imagens/
    ├── artistas/
    └── capas/
```

## O que foi aprendido

Durante a atividade, conseguimos praticar vários conteúdos trabalhados nas aulas, como:

- Criação de páginas utilizando HTML.
- Organização de formulários e tabelas.
- Utilização de links para navegar entre as páginas.
- Personalização de botões e campos com CSS.
- Uso de classes e variáveis CSS.
- Organização de elementos com Flexbox e Grid.
- Adaptação do site para diferentes tamanhos de tela.

## Observação

Nesta etapa, as páginas possuem dados de exemplo inseridos diretamente no HTML. Os formulários e botões fazem parte da estrutura visual do sistema, mas algumas funções ainda precisam ser conectadas ao PHP e ao banco de dados para funcionar completamente.

## Conclusão

Com esse projeto, conseguimos colocar em prática o que aprendemos nas aulas de HTML e CSS, desde a criação das páginas até a parte de estilização.

Também aprendemos a organizar melhor os arquivos e manter um padrão visual em todo o site. O Sistema Musical é o resultado dessa atividade e pode receber novas funcionalidades nas próximas etapas do desenvolvimento.
