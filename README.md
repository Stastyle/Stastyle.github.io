# stastyle.github.io

Personal landing page, served by GitHub Pages at <https://stastyle.github.io/>.

- `index.html` is the whole site: markup, styles, script and fonts in one file.
- The project grid is pulled from the GitHub API on every visit, so a new public
  repository shows up on its own. Forks, archived repos and empty placeholders are skipped.
- `projects.json` holds the editable settings: which repos are featured or hidden,
  Hebrew descriptions, the filter buttons (matched against repo topics), the contact
  email, and `extra` for projects that are not on GitHub or live in private repos.
