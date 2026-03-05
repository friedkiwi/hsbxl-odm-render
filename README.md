# hsbxl-odm-render

We have created photometry images from the terrain of HSBXL. This repository contains a rendering of those images in a way that is suitable for viewing without specialised tools.

This repository is structured as a Maven JavaEE project that outputs a WAR. This allows easy deployment on application servers. The application itself does not rely on JavaEE features at this point. A Github Actions trigger is set to build the WAR file on tag, as well as a ZIP file with the static content for hosting on a normal web server and a push to Github pages.

The application is deployed at https://hsbxl-odm-render.legitimatebusiness.be . 