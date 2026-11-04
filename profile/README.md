# Tacit

A desktop for laptops: an operating system on Arch Linux with its own desktop, apps and design language. Dark only.
Everything works offline and on 4 GB of memory; AI is optional and works with the agent you already use.

[Install](https://tacitos.co/install) · [Website](https://tacitos.co) · [Design guide](https://design.tacitos.co) · [Discord](https://discord.gg/Geg72FUhY)

## What is here

Everything that runs on a Tacit computer is open source.

| | Repository | What it is |
|---|---|---|
| Desktop and apps | [tacit](https://github.com/tacit-os/tacit) | The desktop: the notch, search, Setup, Settings, Pinax, Graphis, Viewer and Praxis |
| | [thyris](https://github.com/tacit-os/thyris) | Tacit's browser, on Chromium's engine |
| System | [agent-host](https://github.com/tacit-os/agent-host) | Runs the AI agents behind Praxis and the notch, and holds what they may do |
| | [portal](https://github.com/tacit-os/portal) | File dialogs, Open with, the keyring prompt and screen sharing |
| | [boot](https://github.com/tacit-os/boot) | The boot and shutdown splash |
| | [backup](https://github.com/tacit-os/backup) | Nightly encrypted backup of your work |
| | [cpu-policy](https://github.com/tacit-os/cpu-policy) | The power mode that follows the charger and the battery |
| | [text](https://github.com/tacit-os/text) | Tacit's text: one gamma for text across Qt, Thyris, GTK and foot |
| | [foot](https://github.com/tacit-os/foot) | The terminal, foot with Tacit's text |
| Look | [tacit-kit](https://github.com/tacit-os/tacit-kit) | Tacit.Kit, the parts Tacit's apps are made of; its guide is [design.tacitos.co](https://design.tacitos.co) |
| | [fonts](https://github.com/tacit-os/fonts) | Tacit Sans, Tacit Mono and Tacit Code |
| | [icons](https://github.com/tacit-os/icons) | Tacit's symbols, cursor and folder icons |
| Building | [tacit-build](https://github.com/tacit-os/tacit-build) | How Tacit is built: its packages, the installer and the ISO |
| Devices | [book4-charge](https://github.com/tacit-os/book4-charge) | Charging for the Samsung Galaxy Book4 Edge |
| Examples | [tacit-music-example](https://github.com/tacit-os/tacit-music-example) | A music player made only of Tacit.Kit's parts, to build your own app on |

## Taking part

Every repository takes pull requests; each one's `CONTRIBUTING.md` says how, and every commit is signed off
(`git commit -s`). Tacit is worked on in its own repositories and published here with each release; a pull request
that is taken goes into Tacit under your name.

Found a problem or have an idea? Open an issue on [tacit](https://github.com/tacit-os/tacit/issues), or tell us in
[Discord](https://discord.gg/Geg72FUhY).

## Licences

Most of Tacit is GPL-3.0. Tacit.Kit and [text](https://github.com/tacit-os/text) are LGPL-3.0, the fonts are under
the SIL Open Font License 1.1, [foot](https://github.com/tacit-os/foot) keeps foot's MIT licence, and the design
guide's text and figures are CC BY 4.0.
