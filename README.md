# Introduction

This package enables target-agnostic layout operations using CSS Grid and Flexbox. Possible uses include UI layouts, page layouts for reports, complex plotting layouts, etc.

It implements Python bindings for [Taffy](https://github.com/dioxuslabs/taffy), an implementation of Grid/Flexbox written in [Rust](https://www.rust-lang.org/). It was originally based on [Stretch](https://vislyhq.github.io/stretch/) (hence the name), but has since migrated to use Taffy.

# Getting Started

Helpful resources to getting started with layouts using CSS Grid and Flexbox are listed below.

### Flexbox

- [Flexbox Froggy](https://flexboxfroggy.com/). This is an interactive tutorial/game that allows you to learn the essential parts of Flexbox in a fun engaging way.
- [A Complete Guide To Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) by CSS Tricks. This is detailed guide with illustrations and comphrehensive written explanation of the different Flexbox properties and how they work.
- [Yoga Playground](https://yogalayout.com/playground)

### CSS Grid

- [CSS Grid Garden](https://cssgridgarden.com/). This is an interactive tutorial/game that allows you to learn the essential parts of CSS Grid in a fun engaging way.
- [A Complete Guide To CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) by CSS Tricks. This is detailed guide with illustrations and comphrehensive written explanation of the different CSS Grid properties and how they work.

# Usage

See [demos](https://github.com/mortencombat/stretchable/tree/main/demos) for examples of basic usage. Keep in mind that the current version of Stretchable is early stage and the API can be expected to change (eg. improve).

# Building

Install Rust with [rustup](https://rustup.rs/) and use `maturin develop` for development and `maturin build [--release]` to build.

# Testing

Install test dependencies and invoke `pytest`. Note that there are approx. 250 tests, the majority of which are run using Selenium with the Chrome WebDriver, and the complete test suite can take a few minutes to complete. Use `pytest --lf` to only run the last-failed tests.

# License

This work is released under the MIT license. A copy of the license is provided in the [LICENSE](https://github.com/mortencombat/stretchable/blob/main/LICENSE) file.
