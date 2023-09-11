# Introduction

This web application is split into:

- GCL code server-side, which exposes endpoints for JS. These endpoints download, store and sample water-realted data from public sources.
- HTML/JS which uses the GreyCat UI and SDK to plot the downloaded data.

# Installation

Simply copy this directory.

# Execution

From the `water` directory:

`$ greycat serve --user=1 --webroot=./webroot` 

starts a web server which exposes the API endpoints defined in `project.gcl`.

Then point the browser to `localhost:8080`.

# Tutorial

