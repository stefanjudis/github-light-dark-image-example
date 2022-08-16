## A test for light/dark mode images using hashes

![Fancy logo](./dark.png#gh-dark-mode-only)
![Fancy logo](./light.png#gh-light-mode-only)

```
![Fancy logo](./dark.png#gh-dark-mode-only)
![Fancy logo](./light.png#gh-light-mode-only)
```
## A test for light/dark mode images using `picture`

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/stefanjudis/github-light-dark-image-example/main/dark.png">
  <img alt="Text changing depending on mode. Light: 'So light!' Dark: 'So dark!'" src="https://raw.githubusercontent.com/stefanjudis/github-light-dark-image-example/main/light.png">
</picture>
```

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/stefanjudis/github-light-dark-image-example/main/dark.png">
  <img alt="Text changing depending on mode. Light: 'So light!' Dark: 'So dark!'" src="https://raw.githubusercontent.com/stefanjudis/github-light-dark-image-example/main/light.png">
</picture>

## A broken test for light/dark mode images using `picture` with relative paths 

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./dark.png">
  <img alt="Text changing depending on mode. Light: 'So light!' Dark: 'So dark!'" src="./light.png">
</picture>
