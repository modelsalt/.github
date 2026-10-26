## Model Salt

Ask a language model for the same thing ten times and you get the same answer ten times. Model Salt gives your model randomness from outside it, so one prompt gives ten different answers that still do what you asked.

![Ten runs of "Generate an SVG of a pelican riding a bicycle" on Claude Opus 5.5: the plain prompt draws the same pelican ten times, with Model Salt nine of the ten are different](pelicans.png)

```sh
npx -y @modelsalt/model-salt setup claude    # or codex, gemini, kimi
```

- **[model-salt](https://github.com/modelsalt/model-salt):** the MCP server, the install commands and every example run
- **Site:** [modelsalt.com](https://modelsalt.com), with the examples side by side
- **Made by** [Chris Benjaminsen](https://chrisbenjaminsen.com). Code under MIT, example runs under CC BY 4.0.
