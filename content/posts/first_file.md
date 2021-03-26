+++
draft = true
heading = "HELLO"
it_s_a_drop_down = "two"
your_text = "This is some text"

+++
# Preview Commands

**Instant previews** allow for you to spin up a development server in our preview environment which will drastically reduce preview times.

To help you get started, we provide [**default commands**](https://forestry.io/docs/previews/build-commands/#default-commands). You can then tailor preview settings to your needs, if your website source lives in a subdirectory for example or if you use a different script to run your preview.

[**How to use instant previews**](https://forestry.io/docs/instant-previews/).

## [**Preview Environment**](https://forestry.io/docs/previews/build-commands/#preview-environment)

All sites are built in a Linux container and have access by default to the following tools:

* Ruby / Bundler for Jekyll websites
* Go / Hugo
* NodeJS, NPM, Yarn for NodeJS based SSG like Gatsby, NextJS, Gridsome, NuxtJS, Eleventy, etc.

Hugo and Jekyll users relying on node modules for their asset pipeline can also use a preview environment embedding NodeJS.

If your project has a **`package.json`** file, your **`node_modules`** will be installed automatically. **You must use NPM or Yarn scripts in your build commands**.

In the advanced settings, you can also provide any custom Docker image hosted on **https://hub.docker.com** if your project has specific dependencies.