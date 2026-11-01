# Crayz OpenClaw Skills

A repository containing a ZIP snapshot of **Awesome OpenClaw Skills**, a community directory of skills for the locally running OpenClaw assistant. Browse skills by category to find integrations, developer tools, and workflow automation ideas.

## What is included

The source material is stored in [awesome-openclaw-skills-main.zip](./awesome-openclaw-skills-main.zip). After extraction, its `awesome-openclaw-skills-main/` directory contains:

| Path inside the archive | Contents |
| --- | --- |
| `README.md` | Collection overview, installation guidance, and category index |
| `categories/` | 32 Markdown lists covering coding, research, automation, communication, and other topics |
| `CONTRIBUTING.md` | Upstream contribution requirements |
| `LICENSE` | MIT license with VoltAgent attribution |

The archive contains a directory of links and descriptions. It does not bundle the OpenClaw application or the source code of every listed skill. This snapshot is not automatically synchronized with upstream.

## Browse locally

```bash
git clone https://github.com/ayazaltai/Crayz-OpenClaw-Skills.git
cd Crayz-OpenClaw-Skills
unzip awesome-openclaw-skills-main.zip
cd awesome-openclaw-skills-main
```

Open `README.md` in a Markdown viewer, then browse the files in `categories/`. No build step is needed to read the collection.

## Use a listed skill

OpenClaw must be installed separately. Follow the selected skill's source documentation for its prerequisites, configuration, and installation. The archived collection documents installation through ClawHub or by copying a skill directory into a workspace's `skills/` directory or `~/.openclaw/skills/`.

Review a skill's implementation and required permissions before installing it. Inclusion in this collection does not mean the skill has been audited. Availability and behavior of linked skills may change after this snapshot.

## Contributing

For changes to this repository's landing page, open a pull request here. For changes to the upstream directory, consult the archived `CONTRIBUTING.md` and the upstream repository's current contribution guidance.

## Attribution and license

The archived collection credits [VoltAgent's Awesome OpenClaw Skills project](https://github.com/VoltAgent/awesome-openclaw-skills). Its `LICENSE` specifies the MIT license, copyright 2026 VoltAgent. Preserve that license and attribution when redistributing the collection. Individual linked skills may use different licenses.
