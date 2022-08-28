# Explicação da divisão de responsabilidades nas pastas

- img => Cuidará apenas das imagens, podendo ser dividida em subpastas que irão conter images de um respectivo contextp

```
Exemplo: /img/men-page/logo.png

A logo png irá pertencer a subpasta men-page,
a qual o seu contexto é a de guardar images da página NIKE-MEN.
```

- pages => Será responsável por guardar as páginas do web site. Aqui ficará o html e cada arquivo é responsável por algo em específico.

```
Exemplo: /pages/kids.html

Esse arquivo html irá representar a página de produtos para crianças.
```

- styles => Terá os arquivos de estilização, caso tenha alguma estilização que é compartilhada em comum entre as páginas, é possível criar uma pasta de **componentes** ou até mesmo colocar em **global.css**.

```
Exemplo:

/styles/global.css => o que toda página terá em comum
/styles/kids.css => estilização apenas da página de kids.
```