# Setup

## Required repository structure

Create or use the special GitHub profile repository:

```text
ParsaKhezli/
└── ParsaKhezli/
    ├── README.md
    └── assets/
        ├── devops-control-plane.svg
        ├── operator-terminal.svg
        └── pipeline-loop.svg
```

The repository must be public and its name must exactly match your GitHub username for GitHub to display `README.md` on your profile.

## Upload with Git

```bash
git clone https://github.com/ParsaKhezli/ParsaKhezli.git
cd ParsaKhezli

cp /path/to/README.md .
cp -r /path/to/assets .

git add README.md assets/
git commit -m "Redesign DevOps profile README"
git push origin main
```

## What works automatically

- All three custom DevOps animations are local SVG files inside your repository.
- Profile views and follower badges use your `ParsaKhezli` username.
- GitHub telemetry cards update from your public GitHub activity.
- The typing animation, technology icons, and contact badges are loaded from public README services.

## Notes

- GitHub may cache external SVG cards for a while after an update.
- Public statistics services can occasionally be rate-limited. The custom local animations are not affected.
- The README intentionally avoids fake repository cards. Add featured projects only after you have public repository URLs worth highlighting.
- Keep `Kubernetes` and `Argo CD` framed as current learning areas until you are comfortable presenting production-level experience.
