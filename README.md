# Raw Image Builder
[![Join the chat at https://gitter.im/hypriot/talk](https://badges.gitter.im/hypriot/talk.svg)](https://gitter.im/hypriot/talk?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://travis-ci.org/hypriot/image-builder-raw.svg)](https://travis-ci.org/hypriot/image-builder-raw) [![GuardRails badge](https://badges.production.guardrails.io/moul/image-builder-raw.svg)](https://www.guardrails.io)

This repo creates a number of blank images for a couple of ARM dev boards.
These images have the necessary partitions, sizes and filesystem - but not actual files.

Currently there is the following image:

* `rpi-raw-image` with two partitions (FAT + EXT4) for the Raspberry Pi

## Contributing

You can contribute to this repo by forking it and sending us pull requests. Feedback is always welcome!

You can build the root filesystem locally with Docker.

```bash
make rpi-raw-image
```


## License

MIT - see the [LICENSE](./LICENSE) file for details.
