# Ziyin Huang's academic homepage

This site uses the Jekyll source from [Minimal Light](https://github.com/yaoyao-liu/minimal-light/tree/dd114c3fef2d97adc1c6b6d46901e0d96ab83a7c).

## Publish on GitHub Pages

1. Put these files at the root of the `main` branch of the public repository `huangziyin1.github.io`. If replacing a previous static version, remove its `.nojekyll` and `index.html` so GitHub Pages can build `index.md` with Jekyll.
2. In **Settings → Pages**, select **Deploy from a branch**, then **main** and **/ (root)**. Click **Save**.
3. Open <https://huangziyin1.github.io/> after the Pages deployment succeeds.

## Edit the homepage

- `_config.yml` holds the sidebar profile and links.
- `index.md` holds the biography and research interests.
- `_data/publications.yml` holds publication details and links.
- `_includes/services.md` holds the conference and journal reviewing entries.
- The sidebar portrait is `assets/img/avatar.png`. Set `avatar` in `_config.yml` to use a different image.
- Publication thumbnails live in `assets/img/publications/`. Each paper's `image`, `image_alt`, and `conference_short` fields control its thumbnail and venue badge. The thumbnails come from figures in the corresponding papers. STM-Net uses [Figure 1 from the preprint](https://arxiv.org/html/2609.39894v1#S2.F1).
