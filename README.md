# Steam Store Assets

Public repository for Steam store page image assets and URLs for multiple games.

## Repository Structure

Assets are organized by game in their respective folders:

```
steamstore/
├── flipworld/
│   ├── support_badge_64.png
│   └── support_badge_256.png
└── [other-games]/
    └── ...
```

## Flipworld

Store page image assets for Flipworld.

### Recommended (High Quality)
Use these for the best appearance on all displays (Steam will scale them down):

- **Support Badge:** `https://raw.githubusercontent.com/Promeduz/steamstore/main/flipworld/support_badge_256.png`
- **Ironheart Item:** `https://raw.githubusercontent.com/Promeduz/steamstore/main/flipworld/item_ironheart_256.png`

### Legacy/Small Versions
- `flipworld/support_badge_64.png` (Note: actually 128px)
- `flipworld/item_ironheart_64.png` (Note: actually 64px)


## Adding New Games

When adding assets for a new game:
1. Create a new folder with the game name
2. Add your assets to that folder
3. Update this README with the new game's assets and URLs

## License

Assets in this repository are part of their respective game projects.
