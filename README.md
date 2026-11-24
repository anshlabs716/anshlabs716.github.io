# AnshLabs

Personal portfolio and live repository explorer for AnshLabs.

- **Website:** https://anshlabs716.github.io
- **GitHub:** https://github.com/anshlabs716
- **Repository file index:** https://anshlabs716.github.io/files.html

The homepage loads current public repositories directly from the GitHub API, with search, sorting, and filters for original projects, forks, and recently active work. The file index is generated from the repositories' default-branch Git trees and includes source, documentation, dotfiles, and assets.

The repository list is dynamic; its count is never hard-coded.

## Run locally

    python3 -m http.server 8000

Open http://localhost:8000.

## Deployment

GitHub Pages publishes the main branch from the repository root.

## License

Website source: MIT (see LICENSE).
