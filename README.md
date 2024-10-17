## ![Logo](static/images (1)-modified.png) Chameleon CSS Framework



**Chameleon** is a utility-first CSS framework designed for building fast and responsive web applications. It offers a comprehensive set of utility classes that make it easy to style your elements without writing custom CSS for every component.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Utilities](#utilities)
- [Colors](#colors)
- [Spacing](#spacing)
- [Typography](#typography)
- [Layout](#layout)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Utility-First Design**: Use predefined utility classes for rapid development.
- **Responsive Design**: Built with mobile-first principles.
- **Lightweight**: Minimal file size for fast loading times.
- **Customizable**: Easily customize variables for your project’s needs.

## Installation

### Via npm

To install Chameleon CSS using npm, run:

```bash
npm install chameleon-css
```

### Via CDN

Alternatively, you can include Chameleon CSS in your project using a CDN:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/chameleon-css@1.0.0/dist/chameleon.min.css">
```

## Usage

To use Chameleon CSS in your HTML, simply include the stylesheet in your `<head>` section:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="path/to/chameleon.min.css">
    <title>Chameleon CSS Example</title>
</head>
<body>
    <div class="bg-blue-500 text-white p-4 rounded-md">
        <h1 class="text-2xl font-bold">Welcome to Chameleon!</h1>
        <p class="text-base">This is a utility-first CSS framework.</p>
    </div>
</body>
</html>
```

## Utilities

Chameleon CSS provides a variety of utility classes:

### Colors

| Class              | Description              |
|--------------------|--------------------------|
| `.bg-blue-500`     | Background color blue     |
| `.text-white`      | Text color white          |
| `.text-gray-800`   | Text color dark gray      |

### Spacing

| Class              | Description              |
|--------------------|--------------------------|
| `.p-1`             | Padding of 0.25rem       |
| `.p-2`             | Padding of 0.5rem        |
| `.m-1`             | Margin of 0.25rem        |
| `.m-2`             | Margin of 0.5rem         |

### Typography

| Class              | Description              |
|--------------------|--------------------------|
| `.text-lg`         | Font size large           |
| `.font-bold`       | Bold font weight          |
| `.text-center`     | Centered text alignment   |

### Layout

| Class              | Description              |
|--------------------|--------------------------|
| `.flex`            | Display flex              |
| `.grid`            | Display grid              |
| `.grid-cols-2`     | Two columns grid layout   |

## Customization

Chameleon CSS uses CSS variables for easy customization. You can override the default variables in your own stylesheets:

```css
:root {
    --color-primary: #4caf50; /* Custom primary color */
}
```

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines on how to contribute to this project.

## License

Chameleon CSS is licensed under the [MIT License](LICENSE).
```

---

## Customization Tips
- **Installation Instructions**: Adjust the installation instructions if you plan to publish your framework to npm or host it on a specific CDN.
- **Utilities Section**: As you add more utility classes, keep this section updated.
- **Customization Section**: Add more details about how users can customize your framework, especially if you introduce CSS variables or theming options.
- **Contributing Guidelines**: If you have specific guidelines for contributors, you can create a `CONTRIBUTING.md` file to link here.

