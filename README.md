# Staffman — Historical Landing-Page Animation Archive

Small historical design / motion repository containing an exported **Lottie / Bodymovin landing-page animation** and related image assets.

The repository does not contain a complete Staffman application, backend, or maintainable frontend source tree. Its primary artifact is a generated `demo.html` file with the Lottie runtime embedded directly into the page.

## Repository structure

```text
animation landing/
  demo.html
  images/
  9QXEx0uzmeQ.jpg
```

There is no root package manager, build configuration, React / Vue application, API server, or database.

## Animation export

`animation landing/demo.html` is a self-contained animation export.

The file embeds the Bodymovin / Lottie JavaScript runtime and rendered animation data in one large HTML document.

This kind of export is useful for:

- design handoff;
- motion preview;
- landing-page animation experiments;
- client / stakeholder review;
- embedding a motion concept without the original After Effects project.

## Source-code boundary

The generated HTML is approximately hundreds of kilobytes and contains minified animation-engine code plus serialized vector / animation data.

It should be treated as a **build artifact**, not as a maintainable application codebase.

For a modern implementation, a cleaner structure would keep:

```text
animation.json
Lottie runtime dependency
small HTML / React wrapper
source design / After Effects file if available
```

rather than committing the entire runtime and animation payload into one generated HTML file.

## Running locally

Because the demo is static, serve it with any simple HTTP server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/animation%20landing/demo.html
```

## Portfolio use

This repository is useful as evidence of historical motion / interaction work:

- landing-page animation;
- Lottie / Bodymovin export workflow;
- web motion handoff;
- integration-oriented design assets.

Do not present it as a full Staffman software product unless the actual product source / case study is stored elsewhere.

## Attribution / source-assets caveat

The repository currently preserves the rendered export rather than a clear source-history document.

Before republishing the animation, verify:

- ownership of the underlying design;
- image rights;
- font licensing;
- any client / commercial-use constraints;
- original Bodymovin / Lottie attribution requirements for the version embedded in the export.

## Current status

**Historical motion-design / landing-animation archive.** The repository contains a working static animation demo, but not the full product or editable source project.

## License

No repository-wide license is assumed by this README. Verify third-party runtime, image, font, and client-content rights before redistribution.