# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

### Changed

- Include only contact information mentioned in the XML file.
- Rename the project to Stitchjob, playing on having a "tailored" job materials.
- All resume inputs and outputs now reside in `resume/`.
- Add `resume/example.xml` along with its LaTeX and PDF outputs.
- Parser reads all children of <resume>...</resume> element in order, allowing
  order of the sections in the XML to carry into the output.
- Introduce <section>...</section> element in place of specialized sections.
- User profile information gets spread over two lines if too much for one.

### Added

- Introduce <skills>...</skills> to contain individual <skill> elements.
- Introduce <description> element.

## [0.0.1] - 2025-06-29

### Added

- Created the project.
