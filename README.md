# Personna Assets

Avatar images for the [Personna](https://github.com/Osiris-Balonga/personna) library.

## Structure

```
avatars/
├── realistic/          # WebP format
│   └── {gender}/
│       └── {ethnicity}/
│           └── {ageGroup}/
│               ├── 001.webp
│               ├── 002.webp
│               └── ...
└── cartoon/            # SVG format
    └── ... (same structure)
```

## Parameters

| Parameter | Values |
|-----------|--------|
| ethnicity | `mixed`, `west_africa` |
| gender | `male`, `female` |
| ageGroup | `child`, `teen`, `young_adult`, `adult`, `senior` |

## CDN Usage

Images are served via jsDelivr CDN:

```
https://cdn.jsdelivr.net/gh/Osiris-Balonga/personna-assets@v1/avatars/realistic/male/mixed/adult/001.webp
```

## License

MIT
