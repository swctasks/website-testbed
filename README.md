# Software Carpentry Website

Testbed for distant assets.

Assets (css, js, image) are pulled from http://swctasks.github.io/assets

When working offline the **make offline** command generates the site with fallback assets.

The idea is to be able

- to work on styles in https://github.com/swctasks/assets:
- be able to visually test changes with a small style guide
- push to master when ok
- trigger a webhook that will make pull request to

  - assets-central repository which is the distant assets serve for the ecosystem
  - any website that is subscribed to receive fallback assets
