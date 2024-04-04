# csmi-m2-stage-2024-playbook
CSMI M2 internship's antora report (playbook project)

This repository contains the playbook project for the CSMI M2 internship's antora report. 

The content source files are available at [csmi-m2-stage-2024](https://github.com/DonnescoPablo/csmi-m2-stage-2024).

## Getting Started

### Prerequisites

- Node.js (v21.0.0)
- npm (v10.2.0)
- npx (v10.2.0)

### Install Antora locally

Switch to the directory `csmi-m2-stage-2024-playbook` and run the following command.

```bash
node -e "fs.writeFileSync('package.json', '{}')" && npm i -D -E @antora/cli@3.1
```

Verify `antora` command is available.

```bash
npx antora -v
```

Next install the site generator package.

```bash
npm i -D -E @antora/site-generator@3.1
```

Verify both the Antora CLI and the site generator are installed.

```bash
npx antora -v
```

### Notes

Always use lower-case for file-names to avoid any problems that may arise due to 
case-insensitivity of the file-system, or web-server.