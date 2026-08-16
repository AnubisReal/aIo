<div align="center">
  <img alt="aIo" src="./Resources/aio-wide.svg">

  <h1>aIo</h1>

  <img alt="iOS 18+" src="https://img.shields.io/badge/iOS-18+-red">
  <img alt="tvOS 26+" src="https://img.shields.io/badge/tvOS-26+-red">
  <img alt="Jellyfin 12.0" src="https://img.shields.io/badge/Jellyfin-12.0-9962be">

  <br><br>

  <a href="https://translate.jellyfin.org/engage/swiftfin/">
    <img alt="Translations" src="https://translate.jellyfin.org/widgets/swiftfin/-/svg-badge.svg">
  </a>
  <a href="https://matrix.to/#/#jellyfin:matrix.org">
    <img alt="Jellyfin on Matrix" src="https://img.shields.io/matrix/jellyfin:matrix.org">
  </a>
  <a href="https://discord.gg/zHBxVSXdBV">
    <img alt="Jellyfin on Discord" src="https://img.shields.io/badge/Talk%20on-Discord-brightgreen">
  </a>
</div>

<p align="center">
  Cliente nativo de <a href="https://github.com/jellyfin/jellyfin">Jellyfin</a> para iOS y tvOS, basado en <a href="https://github.com/jellyfin/Swiftfin">Swiftfin</a> y con identidad propia.
</p>

## Acerca de aIo

aIo conserva la base nativa, la reproducción directa y la compatibilidad de Swiftfin, incorporando una experiencia visual propia y mejoras adicionales para dispositivos Apple.

El proyecto utiliza SwiftUI y VLCKit para ofrecer una experiencia nativa con amplia compatibilidad de formatos multimedia.

## Documentación

- [Compatibilidad de bibliotecas](./Documentation/libraries.md)
- [Reproducción multimedia](./Documentation/players.md)
- [Versiones compatibles de iOS y tvOS](./Documentation/version.md)
- [Problemas frecuentes](./Documentation/common_issues.md)
- [Guía de contribución y configuración](./Documentation/contributing.md)

## Desarrollo

Instala las herramientas y dependencias necesarias antes de abrir el proyecto en Xcode:

```bash
brew bundle --file Brewfile
carthage update --use-xcframeworks
```

Consulta la [guía de contribución](./Documentation/contributing.md) para configurar el equipo de desarrollo, el Bundle ID y el entorno de compilación.

## Traducciones

aIo conserva las traducciones mantenidas por la comunidad de Swiftfin. Puedes colaborar mediante [Weblate](https://translate.jellyfin.org/projects/swiftfin/).

## Licencia y atribución

aIo es un fork independiente de [Swiftfin](https://github.com/jellyfin/Swiftfin) y no es un cliente oficial de Jellyfin. El código derivado se distribuye conforme a la [Mozilla Public License 2.0](./LICENSE.md).

Jellyfin y sus marcas pertenecen a sus respectivos titulares.
