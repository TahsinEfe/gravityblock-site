# GravityBlock Website

The official marketing and support website for **GravityBlock**, a gravity-controlled block puzzle
for iPhone.

## Pages

- `/` — Product overview and App Store marketing page
- `/support/` — Support contact and frequently asked questions

Both pages are static, responsive, accessible, and ready to use as App Store Connect URLs.

## Run locally

No dependencies or build step are required:

```sh
python3 -m http.server 4173
```

Then open [http://localhost:4173](http://localhost:4173).

## Deploy

The repository is configured for Vercel. Import it as a new project and deploy with the default
settings; no framework preset or build command is needed.

## App Store Connect

After deployment, use:

- Marketing URL: `https://<deployment-domain>/`
- Support URL: `https://<deployment-domain>/support/`

## Contact

Support requests: [thsnfylmz2002@gmail.com](mailto:thsnfylmz2002@gmail.com)
