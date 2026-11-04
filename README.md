# AnshLabs

The personal website for AnshLabs, featuring all public repositories and a searchable file-by-file index.

- **Website:** https://anshlabs716.github.io
- **GitHub:** https://github.com/anshlabs716
- **Complete file index:** https://anshlabs716.github.io/files.html

The repository shelf lists all 19 public repositories. The file index includes every tracked file in those repositories, including dotfiles, Markdown, source, documentation, and assets. Its `files.json` manifest is generated from each public repository's default-branch Git tree.

## Run locally

Serve this directory over HTTP (the file index fetches `files.json`):

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deployment

GitHub Pages publishes the `main` branch from the repository root.

## License

The website source is available under the [MIT License](LICENSE).
