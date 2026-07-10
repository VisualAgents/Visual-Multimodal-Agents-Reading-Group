# Visual Multimodal Agents Reading Group

A responsive, single-page GitHub Pages website for a reading-group session on:

- Digital / GUI / OS Agents
- Embodied / Vision-Language-Action Agents

## Files

- `index.html` — complete webpage, including styling
- `.nojekyll` — prevents GitHub Pages from applying Jekyll processing
- `.github/workflows/pages.yml` — optional GitHub Actions deployment workflow

## Deploy with GitHub Pages

### Option A: Deploy from the `main` branch

1. Create a new GitHub repository.
2. Upload all files in this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then save.

The site will be available at:

`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

### Option B: Deploy with GitHub Actions

1. Upload all files, including `.github/workflows/pages.yml`.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **GitHub Actions**.
4. Push a commit to the `main` branch.

## Customize

The webpage is self-contained. Edit `index.html` to update:

- agenda durations
- paper titles, venues, and links
- introductory text
- prepared-by name
- colors and layout

No build tools or external JavaScript libraries are required.
