# clickup-agent-chat Scoop Bucket

Scoop bucket for [clickup-agent-chat](https://github.com/STR-Consulting/clickup-agent-chat) on Windows.

## Structure

- `bucket/clickup-agent-chat.json` — the Scoop manifest

## Updating the Manifest

Updated automatically by the release workflow in STR-Consulting/clickup-agent-chat.

Manual update:
1. Update `version` in `bucket/clickup-agent-chat.json`
2. Update `url` with new version tag
3. Update `hash` with SHA256 of the Windows zip (`certutil -hashfile <zip> SHA256`)
