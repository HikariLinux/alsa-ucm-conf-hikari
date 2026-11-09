# alsa-ucm-conf-hikari

Hikari Linux ALSA Use Case Manager profiles for internal Apple audio hardware.
Install `ucm2/` over the distribution's `alsa-ucm-conf` tree at `/usr/share/alsa/`.
The files describe the hardware supported by the retained snapshot; rebranding
does not add or validate support for new machines.

The `aop_audio` and `macaudio` directory names, card names, and control names are
hardware interfaces and remain unchanged. These profiles work with
`hikari-audio` and compatible upstream audio packages. Packaging must replace
or conflict with `alsa-ucm-conf-asahi` / `alsa-ucm-asahi`, which own the same files.
Upstream Packit jobs have been removed; build metadata is maintained independently.

## Origin and license

Based on the preserved [alsa-ucm-conf-asahi snapshot](https://github.com/HikariLinux/alsa-ucm-conf-asahi/tree/1473329acab595dfef039f38c384ce16674d6b15),
commit `1473329acab595dfef039f38c384ce16674d6b15`. Original history and snapshot tags are retained.
Hikari Linux maintains this project independently; this is not an official
Asahi Linux release. Original copyright and license notices are preserved.
Hikari Linux changes use the same [BSD-3-Clause license](LICENSE.asahi).
