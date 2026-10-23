# R+L Support desktop-local canonical source

Local Git main at D:/ChromeExtensions/r-l-web-translate-support is the canonical source. GitHub, when configured, is publication, backup, code review and CI. No remote change is permitted to automatically pull, reset, merge or install into this local source.

Preserve existing working data, build output and uncommitted user changes. Release/update requires exact source SHA, expected installed SHA, explicit backup and readback. A remote/main divergence means SYNC_CONFLICT; do not force push or auto pull. No runtime deploy or restart is authorized by this source-only policy.
