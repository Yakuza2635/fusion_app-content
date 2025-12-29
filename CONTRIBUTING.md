# Contributing to Fusion Poster Backgrounds

Thanks for your interest in contributing! 🎉

## 🎨 Adding New Posters

### Image Requirements

| Property | Requirement |
|----------|-------------|
| **Dimensions** | 1024 × 1536 px (Poster) |
| **Aspect Ratio** | 2:3 (Portrait) |
| **Format** | PNG |
| **Style** | Clean, cinematic design |

### File Naming Convention

Use the format: `{category}-{name}.png`

Examples:
- `genre-action.png`
- `streaming-netflix.png`
- `collection-marvel.png`

### Folder Structure

Place files in the appropriate subfolder (each folder contains its own JSON config):

```
posters/
├── genres/        → posters-genres.json + genre-{name}.png
├── streaming/     → posters-streaming.json + streaming-{name}.png
├── studios/       → posters-studios.json + studio-{name}.png
├── animation/     → posters-animationstudios.json + animation-{name}.png
├── collections/   → posters-collections.json + collection-{name}.png
└── releases/      → posters-releases.json + release-{name}.png
```

### Steps

1. **Fork** this repository
2. **Create** your poster image(s) following the specs above
3. **Add** images to the correct `posters/{category}/` folder
4. **Update** the relevant JSON file with your new entry
5. **Submit** a Pull Request

### JSON Entry Format

```json
{
  "id": "unique-id",
  "name": "Display Name",
  "category": "Category Name",
  "catalogIds": [],
  "displayMode": "Grid",
  "layout": "Poster",
  "backgroundImageURL": "https://raw.githubusercontent.com/Yakuza2635/fusion/main/posters/{category}/{filename}.png",
  "iconName": "film",
  "showIcon": false,
  "nameDisplayMode": "Hidden",
  "mediaTypeFilter": "All Content",
  "textSize": "Large",
  "textWeight": "Bold",
  "textColor": "#FFFFFF",
  "backgroundColor": "#000000"
}
```

## 📝 Requesting New Posters

No design skills? Request in [Discord](https://discord.gg/wrMgang5) or open a GitHub Issue.

Include:
- Category type (Genre, Streaming Service, Studio, Collection, etc.)
- Specific items to add
- Reference images (optional)

---

Thank you for helping make Fusion better! 🚀
