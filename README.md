# Visualizador de Perfil do GitHub

Visualizador de Perfil do GitHub é uma aplicação web que permite consultar rapidamente informações públicas de qualquer usuário do GitHub, trazendo dados de perfil e repositórios de forma visual, moderna e responsiva.

## Objetivo
Facilitar a visualização de perfis do GitHub, tornando o acesso a informações como avatar, bio, seguidores, repositórios e estatísticas mais acessível e intuitivo, sem necessidade de login ou autenticação.

## Principais Recursos
- Busca de usuários do GitHub pelo nome de usuário
- Exibição de informações do perfil: avatar, nome, bio, localização, seguidores, seguindo
- Listagem dos 10 repositórios mais recentes, com links, estrelas, forks, watchers e linguagem principal
- Layout responsivo para dispositivos móveis e desktop
- Animações e design moderno
- Mensagens de erro amigáveis e feedback visual durante a busca

## Exemplo de Uso
<img src="https://user-images.githubusercontent.com/placeholder/demo-github-viewer.png" alt="Exemplo da interface" width="600"/>

## Como usar
1. Clone este repositório:
	 ```bash
	 git clone <url-do-repositorio>
	 ```
2. Abra o arquivo `index.html` em seu navegador (não é necessário servidor).
3. Digite o nome de usuário do GitHub e clique em "Buscar" ou pressione Enter.
4. Veja as informações do perfil e os repositórios listados na tela.

## Diferenciais Técnicos
- Utiliza a [API pública do GitHub](https://docs.github.com/pt/rest) para buscar dados em tempo real
- Código modularizado em ES6 (separação entre API, visualização e lógica principal)
- CSS moderno com variáveis, responsividade e animações
- Não requer dependências externas ou build

## Estrutura do Projeto
```
index.html                # Página principal
src/
	css/
		animations.css        # Animações customizadas
		reset.css             # Reset de estilos
		responsive.css        # Estilos responsivos
		styles.css            # Estilos principais
	js/
		githubApi.js          # Comunicação com a API do GitHub
		index.js              # Lógica principal da aplicação
		profileView.js        # Renderização do perfil na interface
```

## Funcionalidades
- Busca de usuários do GitHub pelo nome de usuário
- Exibição de informações do perfil: avatar, nome, bio, localização, seguidores, repositórios, etc.
- Layout responsivo e moderno
- Animações visuais para melhor experiência do usuário

## Estrutura do Projeto
```
index.html                # Página principal
src/
	css/
		animations.css        # Animações customizadas
		reset.css             # Reset de estilos
		responsive.css        # Estilos responsivos
		styles.css            # Estilos principais
	js/
		githubApi.js          # Comunicação com a API do GitHub
		index.js              # Lógica principal da aplicação
		profileView.js        # Renderização do perfil na interface
```

## Como usar
1. Clone este repositório:
	 ```bash
	 git clone <url-do-repositorio>
	 ```
2. Abra o arquivo `index.html` em seu navegador.
3. Digite o nome de usuário do GitHub que deseja buscar e visualize as informações do perfil.


## Tecnologias Utilizadas
- HTML5
- CSS3 (com responsividade e animações)
- JavaScript (ES6 Modules)
- API pública do GitHub


## Contribuição
Sugestões, issues e pull requests são bem-vindos! Sinta-se à vontade para contribuir com melhorias, correções ou novas ideias.

## Licença
Este projeto está sob a licença MIT.