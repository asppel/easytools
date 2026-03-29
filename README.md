# EasyTools

Публичная binary-only поставка платформы EasyTools для AutoCAD.

## Latest Public Release

- Version: `1.0.1`
- Installer: [EasyTools.Setup.1.0.1.exe](https://github.com/asppel/easytools/releases/download/v1.0.1/EasyTools.Setup.1.0.1.exe)
- SHA-256: [EasyTools.Setup.1.0.1.exe.sha256](https://github.com/asppel/easytools/releases/download/v1.0.1/EasyTools.Setup.1.0.1.exe.sha256)
- Release Folder: [Releases/1.0.1](./Releases/1.0.1)

## What Is Included

- платформа EasyTools для AutoCAD;
- installer и контрольная сумма SHA-256;
- публичная поставка без исходного кода и без каталога `Contents\Sets`.

## Installer Model

- installer сохраняет графический интерфейс и базовые пользовательские функции;
- installer не зависит от `.NET 8`;
- installer переведён на `.NET Framework 4.8` для уменьшения размера поставки.

## Set Policy

- прикладные наборы публикуются отдельно от платформы;
- версия платформы ведётся по EasyTools;
- версии наборов ведутся независимо;
- `LightingRoad`, `WireSolution`, `PipeExpert`, `TrenchType` и будущие наборы не входят в публичный installer платформы.

## Links

- Project Page: [GitHub Pages](https://asppel.github.io/easytools/)
- Version History: [CHANGELOG.md](./CHANGELOG.md)
