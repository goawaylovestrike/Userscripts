# Quick Porn Search

A userscript that adds a search dropdown to various adult content sites, allowing you to quickly search for content across multiple platforms.

## Features

- **Multi-site Support**: Includes on over 100 sites. Most work but a few don't. If there's a site that doesn't work message me and I'll add it regardless if it's on the include list or not.

- **Smart Search**: Automatically extracts title, performers, and site information from the current page

- **Included Search Engines**: Includes the following search engines, but you can easily add/remove any.
  - 1337x
  - PornoLabs
  - Yandex
  - Google
  - Full Porn
  - WatchPorn.to
  - Hdporn92
  - Porndish
  - Sexuria
  - Porn Horder

- **Mobile Version**: Mobile version automatically enabled when used on movile device

## Usage

1. Navigate to any supported adult content site
2. Look for the search button (🔍) in the top-left corner of the page
3. Click the button to open the search dropdown
4. Select your preferred search engine
5. The script will automatically extract relevant information and perform the search

### Customizing Search Terms

Click the search button and use the checkboxes to customize what information is included in your search:
- **Performers**: Include performer names in the search
- **Title**: Include the video title
- **Site**: Include the site/studio name
- **No Male Performers**: Exclude male performers from the search


## Configuration

You can customize the search engines by editing the `searchButtons` array in the script. Each search engine can have:
- `name`: Display name
- `url`: Search URL with `{query}` as the search term
- `queryTransform`: Optional function to transform the search query

## Technical Details

- **Version**: 5.3
- **License**: MIT
- **Author**: GoAwayLoveStrike
- **Namespace**: https://github.com/goawaylovestrike

## Contributing

Feel free to submit issues or pull requests to improve the script.

## License

This project is licensed under the MIT License - see the [LICENSE](../LICENSE) file for details.
