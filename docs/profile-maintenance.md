# Profile maintenance

This repository publishes the GitHub profile README for [LE0-Lin](https://github.com/LE0-Lin).

## Updating the profile

1. Edit `README.md` on a working branch and preview its rendered Markdown.
2. For project and contribution claims, link to the relevant repository, merged pull request, or completion record. Confirm the linked record supports the wording.
3. Keep credential documents in `assets/credentials/` and check relative links from the README. Inspect documents for information that should remain private before publishing them.
4. Check image links and descriptive alt text, including the light and dark variants used by `<picture>` elements.
5. Open a pull request with a brief description of the change, inspect the diff, and merge when ready.

Keep the main README focused on maintained projects and a short selection of concrete contributions. Add longer contribution histories and completion records to [upstream-work.md](upstream-work.md). Use primary evidence such as merged patches and reproducible project artifacts; third-party profile scores are not evidence of software quality.

## Contribution animation

The workflow in [generate-snake.yml](../.github/workflows/generate-snake.yml) runs daily at 00:00 UTC, on pushes to `main`, and through manual dispatch. It publishes generated SVG files to the `output` branch.

If the animation is missing, inspect the latest workflow run and confirm these files exist on `output`:

- `github-contribution-grid-snake.svg`
- `github-contribution-grid-snake-dark.svg`

The README references those generated files through their raw GitHub URLs. Keep generated animation files out of manual README edits.

## Achievement visibility

Achievement visibility is an account preference, separate from this repository's README. In GitHub **Settings → Public profile → Profile settings**, enable **Show Achievements on my profile** and save the preference to display earned badges.

Reference: [GitHub's achievement visibility documentation](https://docs.github.com/en/account-and-profile/how-tos/contribution-settings/manage-visibility-settings-for-private-contributions-and-achievements).
