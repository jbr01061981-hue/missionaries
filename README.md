# missionaries
# Missionary Profiles Data

This repository contains biographical data for missionaries throughout history, used by the Missionary Profiles Flutter app.

## Structure

```
├── profiles/           # Individual missionary JSON files
├── metadata/          # Index files and search data
├── assets/            # Images and other media
└── README.md          # This file
```

## Data Sources

- **Primary**: Wikipedia/Wikimedia (with proper attribution)
- **Secondary**: Custom research and biographical data
- **Images**: Public domain or Creative Commons licensed

## Profile Format

Each profile follows this JSON structure:

```json
{
  "id": "william-carey",
  "name": "William Carey",
  "dates": {
    "birth": 1761,
    "death": 1834,
    "display": "1761-1834"
  },
  "summary": "English Christian missionary...",
  "locations": [...],
  "timeline": [...],
  "quiz": [...]
}
```

## Attribution

All content from Wikipedia includes proper attribution as required by CC-BY-SA license.

## Contributing

1. Fork this repository
2. Add new missionary profiles in the `profiles/` directory
3. Update `metadata/index.json` with new entries
4. Submit a pull request

## License

MIT License - see LICENSE file for details.

Data content attribution varies by source - see individual profile files.
