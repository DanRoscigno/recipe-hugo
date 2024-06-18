# Recipes build with Hugo and Pagefind

Hugo is a static site generator, and pagefind is a lightweight search tool that does not rely on any external service.

```bash
yarn install
```

### Build the HTML

```bash
hugo
```

### Generate the search index

```bash
npx pagefind --site public --output-subdir _pagefind
```

### Serve the pages

```bash
hugo server -DEF
```
