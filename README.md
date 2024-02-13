# raku-Distro-Meta

A map of "official" raku distributions.

Key
- "*" = good, keep
- "**" = decide
- "***" = broken, drop
- "?" = test needed

Plan

To submit PRs at the various repos to focus attention of raku newcomers on the most likely path to success and to manage out poorly performing options.

Invitation

Please submit Issues and PRs here with your comments of a meta / review / intent nature (or submit directly to the relavant repo)

## rakudo.org

- Downloads
  - Sources
    - Files ***
  - Windows
    - Binary Releases ?
      - File
      - [Scoop](https://scoop.sh/) ?
    - Rakudo Star Bundle
      - [Chocolatey](https://chocolatey.org/packages/rakudostar) ?
      - [Scoop](https://scoop.sh/) ?
  - Linux
    - Binary Releases
      - File ***
    - Distro packages
      - Fedora
        - dnf install rakudo ?
      - Ubuntu/Debian
        - apt-get install rakudo *
      - openSUSE
        - openSUSE Tumbleweed (rolling release)
          - zypper install rakudo ?
        - openSUSE Leap (stable)
          - [click on](https://software.opensuse.org/package/rakudo) ?
      - Alpine
        - apk add rakudo zef ?
      - Gentoo (rolling release)
        - emerge --ask --verbose dev-lang/rakudo ?
      - Alpine Linux
        - apk add rakudo ? (twice!)
      - NixOS
        - NixOS
          - nix-env -iA nixos.rakudo ?
        - Non-NixOS (huh?)
          - nix-env -iA nixpkgs.rakudo ?
    - User Repositories
      - Arch Linux (AUR)
        - rakudo-bin ?
        - rakudo ?
        - rakudo-get ?
      - rakudo-pkg distro packages
        - [rakudo-pkg distro packages](https://nxadm.github.io/rakudo-pkg)
    - MacOS
      - File ***
      - Homebrew
        - brew install rakudo ?
      - MacPorts
        - sudo port install rakudo ?
    - JavaScript
      - [Rakudo.js](https://www.npmjs.com/package/rakudo) ?
    - Other Platforms
      - BSD
        - [pkgsrc.se](pkgsrc.se) ?
  - Other installation methods
    - [Rakubrew](rakubrew.org) ***
    - [Rakudo Star Bundle](https://rakudo.org/star) ?
- Star Bundle
  - Windows
    - 2024.01 ?
  - macOS
    - 2020.01 *
  - Linux, others
    - 2024.01 ?
  - Alternative Options
    - [Pre-built 3rd Party Packages](https://rakudo.org/star/third-party)
      - Docker
        - [docker pull rakudo-star](https://hub.docker.com/_/rakudo-star/) **
      - Chocolatety
        - [choco install rakudostar] (https://chocolatey.org/packages/rakudostar) ?
      - Scoop
        - [scoop install rakudo-star](https://github.com/ScoopInstaller/Main/blob/master/bucket/rakudo-star.json) ?
      - macOS Homebrew
        - [brew install rakudo-star](https://github.com/Homebrew/homebrew-core/blob/master/Formula/rakudo-star.rb) ?

## raku.org

## rakubrew.org

## [rakudo-pkg](https://nxadm.github.io/rakudo-pkg/)

many
