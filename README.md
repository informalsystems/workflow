# The Informal System

Description of The Informal System.

## Local deployment

This section describes how to deploy this guide locally on your system.

### Pre-requisites

Install `mdBook` using [`cargo`](https://doc.rust-lang.org/cargo/):

```bash
cargo install mdbook
```

You also need to install the mdbook plug-in for [`mermaid`](https://mermaid-js.github.io/mermaid/#/) to generate graphs and diagrams, and the `mdbook-toc` plug-in for generating table of contents:

```bash
cargo install mdbook-mermaid
cargo install mdbook-toc
```

### Building and viewing the guide locally

To build and view the guide in your browser, run the `mdbook serve` command from
the root directory:

```bash
mdbook serve
```

#### View the guide

This will host the guide in your local machine. Open your browser and navigate to:

```bash
http://localhost:3000
```

## Adding or editing new content to the guide

Please check the [mdBook documentation](https://rust-lang.github.io/mdBook/index.html) for additional information on how to add new content to the guide.

Basically if you want to add new content to the guide, just add an entry to the `SUMMARY.md` Markdown file which is the TOC page. Then create a page for the entry you've added to the `SUMMARY.md` page. If you don't create the page, but save the `SUMMARY.md` file and build again, `mdBook` will create the page automatically for you.

#### Local development
If you are adding content using your favorite IDE and have a terminal opened running `mdbook serve`, it provides a convenient watch functionality so any changes detected on local files will trigger another build and if you refresh the guide on your browser they will be shown there.

#### Submit your changes
Once you finish adding the new content just commit your changes (`git commit`) and push them to the respository (`git push`).
