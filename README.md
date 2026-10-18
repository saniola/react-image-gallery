# React Image Gallery

A React single-page application for searching and browsing photos from the Unsplash API, with a lightbox modal for full-size viewing.

## Features

- Search photos by keyword via the Unsplash API
- Responsive image gallery grid
- "Load more" pagination with smooth scroll to newly loaded results
- Full-size image modal viewer
- Loading spinner and toast notifications for empty results and errors

## Technology

- React 18
- Vite build tooling
- Axios for HTTP requests to the Unsplash API
- react-modal for the image lightbox
- react-hot-toast for notifications
- react-loader-spinner for the loading state
- Font Awesome icons
- CSS Modules for component styling
- ESLint for linting

## Project structure

```
src/
  api/          Unsplash API request function
  components/   SearchBar, ImageGallery, ImageCard, ImageModal, LoadMoreBtn, Loader, ErrorMessage
  App.jsx       Application state and layout
  main.jsx      Application entry point
```

## Setup

Requires an Unsplash API access key. Create a `.env` file in the project root:

```
VITE_UNSPLASH_ACCESS_KEY=your_unsplash_access_key
```

## Commands

```
npm install      # install dependencies
npm run dev      # start the Vite dev server
npm run build    # build for production
npm run preview  # preview the production build
npm run lint     # run ESLint
```
