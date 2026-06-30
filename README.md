# Everything Search for Raycast

Instant file search powered by [Everything](https://www.voidtools.com/) (Voidtools) engine.

## Prerequisites

- [Everything](https://www.voidtools.com/) by Voidtools must be installed and running
- es.exe comes bundled with Everything

## Usage

- Open Raycast and type "Search Everything"
- Type your search query
- Select a file to open it
- Use Action Panel (`Ctrl+K`) for more options

## Search Syntax

Everything supports powerful search syntax:
- `ext:pdf` — filter by file type
- `folder:D:\path` — limit to folder
- `dm:today` — modified today
- `size:>10mb` — file size filter
- `content:"keyword"` — search within files (requires Everything content indexing)

## Preferences

- **es.exe Path**: Custom path to es.exe (default: `C:\Program Files\Everything\es.exe`)
- **Max Results**: Maximum results to display (default: 50)
