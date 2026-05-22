# Graylog Design System

The Graylog Design System is a shared design language and component library for building consistent, accessible Graylog interfaces.

See the live version at [https://graylog2.github.io/design-system/](https://graylog2.github.io/design-system/).

The [source code](https://github.com/Graylog2/graylog2-server/tree/master/graylog2-web-interface/docs/graylog-luma) for the design system is part of the [graylog2-server](https://github.com/Graylog2/graylog2-server) repository.

## Run documentation locally

1. Clone [graylog2-server](https://github.com/Graylog2/graylog2-server)
2. Go to the `graylog2-web-interface` folder: `cd graylog2-web-interface`
3. Install the web interface dependencies: `yarn install`
4. Go to the design system directory: `cd docs/graylog-luma`
5. Install design system dependencies: `yarn install`
6. Run `yarn storybook`
7. Open `http://localhost:6006`

## Contribute

> This repository contains the Storybook production build and should not be edited by hand.

To contribute, make changes [in the graylog2-server repo](https://github.com/Graylog2/graylog2-server/tree/master/docs/graylog-luma).
