![Fancy logo](./dark.png#gh-dark-mode-only)
![Fancy logo](./light.png#gh-light-mode-only)

## A test for light/dark mode images using hashes

```
![Fancy logo](./dark.png#gh-dark-mode-only)
![Fancy logo](./light.png#gh-light-mode-only)
```
## A test for light/dark mode images using `picture`

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/stefanjudis/github-light-dark-image-example/main/dark.png">
  <img alt="Text changing depending on mode. Light: 'So light!' Dark: 'So dark!'" src="https://raw.githubusercontent.com/stefanjudis/github-light-dark-image-example/main/light.png">
</picture>
