# learning-in-public

Public learning track: GPU computing, video-encoding performance, ML inference
serving. Companion blog is the Hugo site in this repo (theme: hugo-geekblog),
built + deployed by GitHub Actions to GitHub Pages.

## Cadence
- 1 X thread / week (papers, benchmarks, concepts)
- 1 blog post / 2 weeks (with real numbers)
- 1 benchmark report per experiment (methodology + raw output, `content/benchmarks/`)

## Ground rules (binding)
1. **Open data only**: Blender open movies (Big Buck Bunny, Tears of Steel),
   public datasets, synthetic workloads, rented GPUs. Never employer data,
   volumes, topology, incidents, or internal documents.
2. Benchmarks must be reproducible: exact hardware, exact commands, raw output.
3. Negative results get published too.

## Local build
```
hugo server --buildDrafts   # preview
hugo                        # build to public/
```

## Repo layout
- `content/posts/` — weekly learning posts
- `content/benchmarks/` — benchmark reports
- `themes/hugo-geekblog/` — git submodule
