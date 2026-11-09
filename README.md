<h1 align="center">AnsibleBlocks</h1>

<p align="center"><strong>Build and edit Ansible playbooks visually</strong></p>

<p align="center">
  <a href="https://github.com/voipnorm/AnsibleBlocks-releases/releases/latest"><img src="https://img.shields.io/github/v/release/voipnorm/AnsibleBlocks-releases?style=flat-square" alt="Latest release"></a>
  <a href="https://github.com/voipnorm/AnsibleBlocks-releases/releases"><img src="https://img.shields.io/github/downloads/voipnorm/AnsibleBlocks-releases/total?style=flat-square" alt="Downloads"></a>
  <img src="https://img.shields.io/badge/platform-macOS-lightgrey?style=flat-square" alt="macOS">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square" alt="MIT License"></a>
</p>

<p align="center">
  <a href="https://github.com/voipnorm/AnsibleBlocks-releases/releases/latest"><strong>Download for macOS</strong></a>
  · <a href="https://github.com/voipnorm/AnsibleBlocks-packs">Browse block packs</a>
</p>

## Official release repository

This is the public distribution repository for AnsibleBlocks. It hosts installers, release notes, and the files used by the in-app updater. The application source is maintained separately.

## What you can do

- Build plays, tasks, handlers, and control flow with drag-and-drop blocks.
- Import YAML, edit it alongside your blocks, and export a playbook for Ansible.
- Inspect the playbook structure in Flow View and preview templates with inventory variables.
- Add module blocks for Cisco, RoomOS, cloud platforms, and other collections through Pack Manager.
- Use the bundled CLI to discover available blocks and create or update unsaved drafts while the app is open.

## Download and install

1. Open the [latest release](https://github.com/voipnorm/AnsibleBlocks-releases/releases/latest) and download the `AnsibleBlocks-{version}-universal.dmg` asset.
2. Open the disk image and drag **AnsibleBlocks** to **Applications**.
3. Open AnsibleBlocks from Applications and choose **New** or **Import**.

The public installer contains a signed and notarized universal app for Apple silicon and Intel Macs. To run exported playbooks, use Ansible and the required collections on your Ansible controller.

## Updates

AnsibleBlocks can notify you when a newer public release is available. To check manually, open **Settings → Updates → Check Now**. When an update is offered, choose **Download**, then **Restart & Update**.

Block packs have their own release cycle. Use **Packs → Available** to install or upgrade them. [AnsibleBlocks Packs](https://github.com/voipnorm/AnsibleBlocks-packs)

## Support and maintenance

AnsibleBlocks is maintained by Chris Norman. For help, use the contact options on the maintainer’s GitHub profile. Include your app version, macOS version, and steps to reproduce the issue. Use a sample playbook with credentials removed. [Maintainer profile](https://github.com/voipnorm)

## License

The materials in this repository are available under the [MIT License](LICENSE).
