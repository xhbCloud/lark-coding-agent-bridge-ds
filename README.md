# lark-channel-bridge-ds

Fork of [lark-channel-bridge](https://github.com/zarazhangrui/feishu-claude-code-bridge) with Windows + DeepSeek compatibility fixes.

## Fixes

- **Windows spawn fix** — uses full `.exe` path instead of relying on system PATH
- **Resume validation** — removed non-existent `--no-check-update` flag; uses correct binary path
- **Race condition fix** — removed `closeSilentStdout` 50ms destroy that caused empty replies
- **ESM compat** — removed `require('fs')` from ESM context


