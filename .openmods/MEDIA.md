# OpenMods Demo Mod 1 — Gallery

<!--
  This file curates the gallery shown on the OpenMods mod page.
  Format: - [type:label](url-or-filename)
    type   = image | video | thumbnail
    label  = free-form caption / identifier (informational for now)
    url    = either a filename inside .openmods/media/ or a full https:// URL

  Lines that don't match the format (like this comment, headings,
  blank lines, or "// trailing notes") are simply ignored on sync,
  so use them freely to organize the file.

  Full reference: https://openmods.net/docs?section=media
-->

## Thumbnail

The first `thumbnail:` entry wins and becomes the mod's hero image.
It is **not** added to the gallery automatically — list it again as
`image:` if you also want it in the carousel.

- [thumbnail:cover](demo-img-4.png)

## Showcase

Local filenames are resolved against `.openmods/media/` and rewritten
to GitHub raw URLs at sync time. Order in this list = order in the gallery.

- [image:gameplay-1](demo-img-1.png)
- [image:gameplay-2](demo-img-2.png)
- [image:gameplay-3](demo-img-3.png)
- [image:hero-shot](demo-img-4.png) // same file as the thumbnail — duplicates are allowed on purpose

<!--
  Other things you can do:

  Embed YouTube or Vimeo videos by pasting the URL directly:
    - [video:trailer](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)
    - [video:teaser](https://vimeo.com/YOUR_VIDEO_ID)

  Reference media from another GitHub repo by using its raw URL:
    - [image:cross-repo](https://raw.githubusercontent.com/owner/repo/main/screenshots/01.png)

  Drop in a local mp4/webm clip by placing it in .openmods/media/ and
  referencing it the same way as an image:
    - [video:walkthrough](walkthrough.mp4)
-->
