# ig-media

Image host for my Instagram publishing pipeline.

Files under `posts/` are uploaded automatically by `publish.py`. Instagram's
servers fetch each image from its `raw.githubusercontent.com` URL to build the
post.

**This repo must stay public.** Instagram fetches images anonymously and cannot
authenticate as me, so making it private silently breaks publishing.

Nothing here is sensitive — images only. No tokens or credentials.