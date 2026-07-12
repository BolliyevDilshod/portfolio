# Portfolio — Dilshod Bolliyev

Static one-page portfolio landing page (`index.html`, no build step).

## Local preview
Just open `index.html` in a browser, or:

```bash
python3 -m http.server 8000
```

## Deploy to GitLab Pages
This repo already includes `.gitlab-ci.yml`. Once pushed to a GitLab project with CI/CD enabled,
the site will be published automatically at:

```
https://<your-username>.gitlab.io/<repo-name>/
```

Push to the `main` branch to trigger the pipeline.
