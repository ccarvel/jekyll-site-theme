# A Complete Bibliography of Sheldon Pollock

Built using [Ed](https://minicomp.github.io/ed/) by Alex Gil.

## Modernized for Jekyll 4.4.1 and Ruby 3.4.4

This Jekyll theme has been updated to work with modern versions of Ruby and Jekyll:

- **Ruby**: 3.4.x
- **Jekyll**: 4.4.1
- **Jekyll Scholar**: Latest compatible version

## Installation

### Prerequisites

- Ruby 3.4.x
- Bundler gem

### Setup

1. Clone or download this repository
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```

The site will be available at `http://127.0.0.1:4000`

## Changes Made for Jekyll 4.x Compatibility

### Configuration Updates
- Removed deprecated `incremental` build option
- Updated `plugins` syntax to modern YAML list format
- Removed deprecated `use_raw_bibtex_entry` option from jekyll-scholar configuration

### Dependency Updates
- Updated Jekyll dependency to `~> 4.4.0`
- Added `webrick` gem for local development server
- Updated bundler and rake development dependencies
- Specified Ruby version constraint `~> 3.4.0`

### Styling Updates
- Modernized Sass imports from `@import` to `@use` syntax
- Updated theme version to 2.0.0

## Theme Structure

This theme uses the Ed Jekyll theme, specifically designed for minimal digital editions and bibliographies. It includes:

- Bibliography management with Jekyll Scholar
- Responsive design optimized for academic content
- Search functionality
- Collections for organizing texts and references

## Bibliography Management

The theme uses Jekyll Scholar for bibliography management:
- Bibliography files are stored in `_bibliography/`
- Supports multiple bibliography formats (BibTeX)
- Chicago fullnote citation style configured by default

## License

This theme maintains the original MIT license from the Ed theme.