# Upload Widget

This project is an upload widget built with React, Zustand, and Tailwind CSS. It allows users to upload files, compress images, and track the upload progress.

## Features

- File upload with progress tracking
- Image compression before upload
- Cancel and retry uploads
- Responsive design with Tailwind CSS

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/thiagoskbnsk/upload-widget.git
   cd upload-widget
   ```

2. Install dependencies:

   ```sh
   pnpm install
   ```

## Usage

### Development

To start the development server, run:

```sh
pnpm dev
```

### Build

To build the project for production, run:

```sh
pnpm build
```

### Preview

To preview the production build, run:

```sh
pnpm preview
```

## Configuration

### Tailwind CSS

Tailwind CSS is configured in the `tailwind.config.js` file. You can customize the theme and add plugins as needed.

### Zustand Store

The Zustand store is defined in `src/store/uploads.ts`. It manages the state of file uploads, including adding, canceling, and retrying uploads.

## Dependencies

- React
- Zustand
- Tailwind CSS
- Axios
- Vite

## License

This project is licensed under the MIT License.
