---
layout: app

permalink: /Winds/
description: https://getstream.io/winds

icons:
  - Winds/icons/512x512/winds.png

screenshots:
  - Winds/screenshot.png

authors:

links:

desktop:
  Desktop Entry:
    Name: Winds
    Comment: https://getstream.io/winds
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: winds
    X-AppImage-Version: 2.0.244
    X-AppImage-BuildId: f2f17440-603a-11a8-23e8-4d459dda1194
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  private: true
  author: Winds Team <winds@getstream.io>
  license: MIT
  repository: https://github.com/getstream/winds.git
  bugs:
    url: https://github.com/getstream/winds/issues
  homepage: "./"
  main: build/electron.js
  dependencies:
    algoliasearch: "^3.27.1"
    axios: "^0.18.0"
    babel-plugin-inline-dotenv: "^1.1.2"
    electron-boilerplate: "^1.1.1"
    electron-google-analytics: "^0.1.0"
    electron-is: "^2.4.1"
    electron-is-dev: "^0.3.0"
    electron-log: "^2.2.14"
    electron-open-link-in-browser: "^1.0.2"
    electron-publisher-s3: "^20.14.0"
    electron-remote: "^1.2.0"
    electron-updater: "^2.21.10"
    geopattern: "^1.2.3"
    github-buttons: "^0.0.1-security"
    global: "^4.3.2"
    history: "^4.7.2"
    install: "^0.11.0"
    is-electron: "^2.1.0"
    is-windows: "^1.0.2"
    md5: "^2.2.1"
    moment: "^2.22.1"
    moment-duration-format: "^2.2.2"
    node-notifier: "^5.2.1"
    node-sass-chokidar: "^1.3.0"
    numeral: "^2.0.6"
    opn: "^5.3.0"
    query-string: "^6.1.0"
    raven-js: "^3.25.2"
    rc-slider: "^8.6.1"
    react: "^16.3.2"
    react-audio-player: "^0.9.0"
    react-dom: "^16.3.2"
    react-dragula: "^1.1.17"
    react-dropzone: "^4.2.9"
    react-github-button: "^0.1.11"
    react-html-parser: "^2.0.2"
    react-image: "^1.3.1"
    react-modal: "^3.4.4"
    react-popover: "^0.5.6"
    react-redux: "^5.0.7"
    react-router-dom: "^4.2.2"
    react-waypoint: "^8.0.1"
    redux: "^4.0.0"
    rss-finder: "^2.0.5"
    trianglify: "^1.2.0"
    version-bump-prompt: "^4.1.0"
---
