# Vox Villalobos - Author Website

A modern, responsive author website built with Astro for horror fiction writer Vox Villalobos. Features a dark, atmospheric design with bilingual support (English/Spanish) and smooth navigation.

## ✨ Features

- **Dark Horror Theme**: Pure black background with green accents
- **Bilingual Support**: English/Spanish language switching with keyboard shortcut (E key)
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Smooth Navigation**: Fixed navbar with active section highlighting
- **Typography**: Frijole font for titles, EB Garamond for body text
- **Modern Stack**: Astro, TypeScript, Tailwind CSS

## 🎨 Design

- **Color Scheme**: Black background with green-400 accents
- **Typography**: 
  - Frijole (display font for titles)
  - EB Garamond (serif for body text)
- **Layout**: Single-page design with smooth scrolling sections
- **Icons**: Custom SVG icons for social media links

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd vox-author-page
```

2. Install dependencies
```bash
npm install
```

3. Start development server
```bash
npm run dev
```

4. Open [http://localhost:4322](http://localhost:4322) in your browser

## 📁 Project Structure

```
src/
├── components/
│   ├── HomeSection.astro      # Hero section with name and subtitle
│   ├── WritingSection.astro   # Writing portfolio section
│   ├── AboutSection.astro     # About and social media links
│   ├── MyWriting.astro        # Short stories list
│   ├── LanguageSwitcher.astro # Bilingual language switcher
│   └── Welcome.astro          # Main page component
├── layouts/
│   └── Layout.astro           # Main layout with navbar and footer
├── pages/
│   └── index.astro            # Homepage
└── styles/
    └── global.css             # Global styles and Tailwind imports
```

## 🌐 Language Support

The website supports both English and Spanish:

- **Switch Languages**: Click the globe icon in the navbar or press `E` key
- **Persistent**: Language choice is saved in localStorage
- **Complete Translation**: All text content is translated

## 🛠️ Available Scripts

| Command | Action |
|---------|--------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build |

## 🎯 Sections

- **Home**: Author name and genre
- **My Writing**: Published short stories with links
- **About**: Biography and social media links

## 📱 Responsive Design

- Mobile-first approach
- Breakpoints: sm (640px), md (768px), lg (1024px)
- Optimized typography scaling
- Touch-friendly navigation

## 🔧 Customization

### Adding New Stories
Edit `src/components/MyWriting.astro` to add new published works.

### Updating Translations
Modify the `translations` object in `src/components/LanguageSwitcher.astro`.

### Styling Changes
Update `src/styles/global.css` for global styles or modify individual component styles.

## 📄 License

This project is for Vox Villalobos' personal author website.