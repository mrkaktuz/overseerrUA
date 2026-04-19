> **\ud83c\uddfa\ud83c\udde6 OverseerrUA** — Ukrainian fork of Overseerr with UA audio/subtitles info from [Kinobaza](https://kinobaza.com.ua) and Ukrainian localization.
> Docker image: `ghcr.io/mrkaktuz/overseerr:latest` **(linux/amd64 only)**

---

> **\u26a0\ufe0f Overseerr is being superseded by [Seerr](https://github.com/seerr-team/seerr)**, a unified project merging Overseerr and Jellyseerr. This repository will no longer receive new features or major updates. We recommend migrating to Seerr for continued support and development. See the [Seerr migration guide](https://docs.seerr.dev/migration-guide) for details.

<p align="center">
<img src="./public/logo_full.svg" alt="Overseerr" style="margin: 20px 0;">
</p>
<p align="center">
<img src="https://github.com/sct/overseerr/workflows/Overseerr%20Release/badge.svg?branch=master" alt="Overseerr Release" />
<img src="https://github.com/sct/overseerr/workflows/Overseerr%20CI/badge.svg" alt="Overseerr CI">
</p>
<p align="center">
<a href="https://discord.gg/overseerr"><img src="https://img.shields.io/discord/783137440809746482" alt="Discord"></a>
<a href="https://hub.docker.com/r/sctx/overseerr"><img src="https://img.shields.io/docker/pulls/sctx/overseerr" alt="Docker pulls"></a>
<a href="https://hosted.weblate.org/engage/overseerr/"><img src="https://hosted.weblate.org/widgets/overseerr/-/overseerr-frontend/svg-badge.svg" alt="Translation status" /></a>
<a href="https://github.com/sct/overseerr/blob/develop/LICENSE"><img alt="GitHub" src="https://img.shields.io/github/license/sct/overseerr"></a>
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
<a href="#contributors-"><img alt="All Contributors" src="https://img.shields.io/badge/all_contributors-112-orange.svg"/></a>
<!-- ALL-CONTRIBUTORS-BADGE:END -->
</p>

**Overseerr** is a free and open source software application for managing requests for your media library. It integrates with your existing services, such as **[Sonarr](https://sonarr.tv/)**, **[Radarr](https://radarr.video/)**, and **[Plex](https://www.plex.tv/)**!

## Current Features

- Full Plex integration. Authenticate and manage user access with Plex!
- Easy integration with your existing services. Currently, Overseerr supports Sonarr and Radarr. More to come!
- Plex library scan, to keep track of the titles which are already available.
- Customizable request system, which allows users to request individual seasons or movies in a friendly, easy-to-use interface.
- Incredibly simple request management UI. Don't dig through the app to simply approve recent requests!
- Granular permission system.
- Support for various notification agents.
- Mobile-friendly design, for when you need to approve requests on the go!

With more features on the way! Check out our [issue tracker](https://github.com/sct/overseerr/issues) to see the features which have already been requested.

## Getting Started

Check out our documentation for instructions on how to install and run Overseerr:

https://docs.overseerr.dev/getting-started/installation

## Preview

<img src="./public/preview.jpg">

## Support

- Check out the [Overseerr Documentation](https://docs.overseerr.dev/) before asking for help. Your question might already be in the [FAQ](https://docs.overseerr.dev/support/faq).
- You can get support on [Discord](https://discord.gg/overseerr).
- You can ask questions in the Help category of our [GitHub Discussions](https://github.com/sct/overseerr/discussions).
- Bug reports and feature requests can be submitted via [GitHub Issues](https://github.com/sct/overseerr/issues).

## API Documentation

Our documentation is built on every commit and hosted at https://api-docs.overseerr.dev

You can also access the API documentation from your local Overseerr install at http://localhost:5055/api-docs

## Community

You can ask questions, share ideas, and more in [GitHub Discussions](https://github.com/sct/overseerr/discussions).

If you would like to chat with other members of our growing community, [join the Overseerr Discord server](https://discord.gg/overseerr)!

Our [Code of Conduct](https://github.com/sct/overseerr/blob/develop/CODE_OF_CONDUCT.md) applies to all Overseerr community channels.

## Contributing

You can help improve Overseerr too! Check out our [Contribution Guide](https://github.com/sct/overseerr/blob/develop/CONTRIBUTING.md) to get started.

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://sct.dev"><img src="https://avatars1.githubusercontent.com/u/234213?v=4?s=100" width="100px;" alt="sct"/><br /><sub><b>sct</b></sub></a><br /><a href="https://github.com/sct/overseerr/commits?author=sct" title="Code">💻</a> <a href="#design-sct" title="Design">🎨</a> <a href="#ideas-sct" title="Ideas, Planning, & Feedback">🤔</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/azoitos"><img src="https://avatars2.githubusercontent.com/u/26529049?v=4?s=100" width="100px;" alt="Alex Zoitos"/><br /><sub><b>Alex Zoitos</b></sub></a><br /><a href="https://github.com/sct/overseerr/commits?author=azoitos" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/OwsleyJr"><img src="https://avatars3.githubusercontent.com/u/8635678?v=4?s=100" width="100px;" alt="Brandon Cohen"/><br /><sub><b>Brandon Cohen</b></sub></a><br /><a href="https://github.com/sct/overseerr/commits?author=OwsleyJr" title="Code">💻</a> <a href="https://github.com/sct/overseerr/commits?author=OwsleyJr" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Ahreluth"><img src="https://avatars2.githubusercontent.com/u/75682440?v=4?s=100" width="100px;" alt="Ahreluth"/><br /><sub><b>Ahreluth</b></sub></a><br /><a href="#translation-Ahreluth" title="Translation">🌍</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/KovalevArtem"><img src="https://avatars0.githubusercontent.com/u/36500228?v=4?s=100" width="100px;" alt="KovalevArtem"/><br /><sub><b>KovalevArtem</b></sub></a><br /><a href="#translation-KovalevArtem" title="Translation">🌍</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/GiyomuWeb"><img src="https://avatars0.githubusercontent.com/u/62489209?v=4?s=100" width="100px;" alt="GiyomuWeb"/><br /><sub><b>GiyomuWeb</b></sub></a><br /><a href="#translation-GiyomuWeb" title="Translation">🌍</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/angrycuban13"><img src="https://avatars3.githubusercontent.com/u/39564898?v=4?s=100" width="100px;" alt="Angry Cuban"/><br /><sub><b>Angry Cuban</b></sub></a><br /><a href="https://github.com/sct/overseerr/commits?author=angrycuban13" title="Documentation">📖</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/jvennik"><img src="https://avatars3.githubusercontent.com/u/6672637?v=4?s=100" width="100px;" alt="jvennik"/><br /><sub><b>jvennik</b></sub></a><br /><a href="#translation-jvennik" title="Translation">🌍</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/darknessgp"><img src="https://avatars0.githubusercontent.com/u/1521243?v=4?s=100" width="100px;" alt="darknessgp"/><br /><sub><b>darknessgp</b></sub></a><br /><a href="https://github.com/sct/overseerr/commits?author=darknessgp" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/saltydk"><img src="https://avatars1.githubusercontent.com/u/6587950?v=4?s=100" width="100px;" alt="salty"/><br /><sub><b>salty</b></sub></a><br /><a href="#infra-saltydk" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Shutruk"><img src="https://avatars2.githubusercontent.com/u/9198633?v=4?s=100" width="100px;" alt="Shutruk"/><br /><sub><b>Shutruk</b></sub></a><br /><a href="#translation-Shutruk" title="Translation">🌍</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/krystiancharubin"><img src="https://avatars2.githubusercontent.com/u/17775600?v=4?s=100" width="100px;" alt="Krystian Charubin"/><br /><sub><b>Krystian Charubin</b></sub></a><br /><a href="#design-krystiancharubin" title="Design">🎨</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/kieron"><img src="https://avatars2.githubusercontent.com/u/8655212?v=4?s=100" width="100px;" alt="Kieron Boswell"/><br /><sub><b>Kieron Boswell</b></sub></a><br /><a href="https://github.com/sct/overseerr/commits?author=kieron" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/samwiseg0"><img src="https://avatars1.githubusercontent.com/u/2241731?v=4?s=100" width="100px;" alt="samwiseg0"/><br /><sub><b>samwiseg0</b></sub></a><br /><a href="#question-samwiseg0" title="Answering Questions">💬</a> <a href="#infra-samwiseg0" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
