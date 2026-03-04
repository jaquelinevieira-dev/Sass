# Projeto Sass

Este projeto demonstra o uso de **Sass** (Syntactically Awesome Style Sheets), um pré-processador CSS que ajuda a escrever estilos de forma mais organizada, reutilizável e eficiente.

##  Demonstração

Veja o projeto rodando:https://jaquelinevieira-dev.github.io/Sass/

##  Estrutura do Projeto

- `css/_variables.scss`: Variáveis de cor, fonte e margens usadas no projeto.
- `css/_base.scss`: Estilos base e reset do CSS.
- `css/_mixins.scss`: Mixins para efeitos e reset de listas.
- `css/_extends.scss`: Placeholders para extender estilos de alertas.
- `css/main.scss`: Arquivo principal que importa os outros arquivos Sass.
- `css/main.css`: CSS gerado a partir do Sass (não editar manualmente).
- `css/main.css.map`: Mapa de origem para depuração.

## Como usar e compilar Sass

1. **Clone o repositório:**
   ```bash
   git clone https://jaquelinevieira-dev.github.io/Sass/
   ```

2. **Instale o Sass globalmente** (caso não tenha):
   ```bash
   npm install -g sass
   ```

3. **Compile o Sass para CSS:**
   ```bash
   sass css/main.scss css/main.css
   ```

4. **Abra o `index.html`** em seu navegador para visualizar o resultado.

## Recursos Sass utilizados

- **Variáveis** para cores, fontes e margens.
- **Mixins** para efeitos reutilizáveis.
- **Extends** (placeholders) para componentes de alerta.
- **Nestings** para organização dos estilos.


## Licença

Este projeto está sob a licença MIT.

