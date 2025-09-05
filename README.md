# Red Hat Linux Theme for Vencord

A Discord theme inspired by Red Hat Enterprise Linux and GNOME Adwaita design language. This theme brings the clean, professional look of RHEL to your Discord experience.

## Features

- **Red Hat Brand Colors**: Uses official Red Hat Red (#CC0000) and Adwaita color palette
- **Cantarell Font**: RHEL's default GNOME font for authentic Linux feel
- **Adwaita Styling**: Rounded corners, subtle shadows, and clean design elements
- **Status Indicators**: Color-coded status indicators matching GNOME conventions
- **Responsive Design**: Optimized for various Discord layouts

## Installation

### Method 1: Direct Import (Recommended)

1. Open Vencord Settings
2. Go to Themes → Edit Themes
3. Click the "+" button to add a new theme
4. Copy and paste the contents of `RedHatLinux.theme.css`
5. Save and enable the theme

### Method 2: Local File

1. Download `RedHatLinux.theme.css` to your Vencord themes folder:
   - **Windows**: `%APPDATA%/Vencord/themes/`
   - **macOS**: `~/Library/Application Support/Vencord/themes/`
   - **Linux**: `~/.config/Vencord/themes/`
2. Restart Discord
3. Enable the theme in Vencord Settings

## Customization

The theme uses CSS custom properties for easy customization. You can modify these variables in the theme file:

```css
--rgb-highlight: 204, 0, 0;        /* Red Hat Red */
--rgb-background: 246, 245, 244;   /* Adwaita Background */
--rgb-text: 46, 52, 54;            /* Adwaita Text */
--custom-title-text: "Red Hat Enterprise Linux"; /* Custom title */
```

## Color Palette

- **Red Hat Red**: #CC0000 (Primary accent)
- **Adwaita Background**: #F6F5F4 (Main background)
- **Adwaita Text**: #2E3436 (Text color)
- **Online Status**: #2ECC71 (Green)
- **Idle Status**: #F1C40F (Yellow)
- **DND Status**: #E74C3C (Red)
- **Streaming Status**: #9B59B6 (Purple)

## Requirements

- Vencord (Discord client mod)
- Internet connection (for Google Fonts)

## Troubleshooting

### Theme Not Loading
- Ensure you have Vencord installed and enabled
- Check that the theme is enabled in Vencord Settings
- Try refreshing Discord (Ctrl+R)

### Font Not Loading
- Check your internet connection
- Google Fonts may be blocked by your network
- The theme will fall back to system fonts

### Styling Issues
- Discord frequently updates their CSS classes
- Some selectors may break with Discord updates
- Check the Vencord community for updated selectors

## Contributing

Feel free to submit issues and enhancement requests! This theme is open source and contributions are welcome.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Red Hat for the brand colors and design inspiration
- GNOME Project for the Adwaita design language
- Vencord team for the theming platform
- Discord for the amazing platform

## Links

- [GitHub Repository](https://github.com/Guacrs/RHLtheme)
- [Live Theme URL](https://guacrs.github.io/RHLtheme/main.css)
- [Vencord](https://vencord.dev/)
- [Red Hat Brand Guidelines](https://www.redhat.com/en/about/brand/standards)

---

**Note**: This theme is not affiliated with Red Hat, Inc. or Discord. It's a fan-made theme inspired by Red Hat Enterprise Linux.
