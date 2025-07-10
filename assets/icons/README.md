# SVG Icon Set

This directory contains a comprehensive set of SVG icons designed for use in your Flutter application. All icons are created with a 24x24 viewBox and use consistent styling with `stroke="currentColor"` to inherit the current text color.

## Available Icons

### Basic UI & Navigation
- `home.svg` - Home/house icon
- `menu.svg` - Hamburger menu (three lines)
- `close.svg` - Close/X icon
- `back.svg` - Back/left arrow
- `forward.svg` - Forward/right arrow
- `arrow-up.svg` - Up arrow
- `arrow-down.svg` - Down arrow
- `search.svg` - Search/magnifying glass

### Actions & Operations
- `add.svg` - Plus/add icon
- `edit.svg` - Edit/pencil icon
- `delete.svg` - Delete/trash can icon
- `save.svg` - Save/floppy disk icon
- `share.svg` - Share/upload icon
- `download.svg` - Download icon
- `upload.svg` - Upload icon

### Media Controls
- `play.svg` - Play button
- `pause.svg` - Pause button
- `stop.svg` - Stop button

### Communication
- `mail.svg` - Email/mail icon
- `phone.svg` - Phone icon
- `message.svg` - Message/chat bubble icon

### Files & Users
- `file.svg` - Document/file icon
- `folder.svg` - Folder icon
- `user.svg` - Single user profile icon
- `users.svg` - Multiple users/group icon

### Status & Feedback
- `check.svg` - Checkmark/success icon
- `warning.svg` - Warning/alert triangle
- `info.svg` - Information circle icon
- `heart.svg` - Heart/like icon
- `star.svg` - Star/favorite icon

### Visibility & Security
- `eye.svg` - Show/view icon
- `eye-off.svg` - Hide/hidden icon
- `lock.svg` - Lock/security icon

### Tools & Settings
- `settings.svg` - Settings/gear icon
- `camera.svg` - Camera icon

## Usage in Flutter

To use these icons in your Flutter app, you can load them as assets. First, make sure to declare them in your `pubspec.yaml`:

```yaml
flutter:
  assets:
    - assets/icons/
```

Then use them in your Flutter widgets:

```dart
// Using SvgPicture from flutter_svg package
SvgPicture.asset(
  'assets/icons/home.svg',
  width: 24,
  height: 24,
  colorFilter: ColorFilter.mode(Colors.blue, BlendMode.srcIn),
)
```

## Customization

All icons use `stroke="currentColor"` and `fill="none"`, making them easy to customize:
- **Color**: Use `colorFilter` or `color` properties
- **Size**: Adjust `width` and `height` properties
- **Stroke width**: Edit the SVG's `stroke-width` attribute (default is 2)

## Icon Style

These icons follow a consistent design system:
- 24x24 viewBox
- 2px stroke width
- Rounded line caps and joins
- Outlined style (no fills)
- Clean, minimal aesthetic