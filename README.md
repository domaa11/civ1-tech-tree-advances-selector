# Civilization I Tech Tree Explorer

An interactive web tool for exploring the technology prerequisites in Sid Meier's Civilization I. Discover what technologies you need to research in order to unlock any specific advancement.

## 🎮 Live Demo

**[Try it out here!](https://[your-username].github.io/civ1-tech-tree-advances-selector/)**

## ✨ Features

- **Interactive Tech Tree**: Select any technology to see its complete prerequisite chain
- **Smart Search**: Filter technologies by name to quickly find what you're looking for
- **Visual Categories**: Color-coded display showing what each technology unlocks:
  - 🟡 **Units** (Military units)
  - 🟢 **Buildings** (City improvements)
  - 🟣 **Wonders** (World wonders)
  - 🔴 **Other** (Governments, terrain improvements, etc.)
- **Click Navigation**: Click on any prerequisite to make it your new target
- **Complete Data**: All 67 technologies from Civilization I with accurate prerequisite relationships

## 🎯 How to Use

1. **Select a Technology**: Choose from the dropdown list or use the search filter
2. **View Prerequisites**: See the complete chain of technologies you need to research (in order)
3. **Explore Further**: Click on any prerequisite to explore its requirements
4. **Understand Benefits**: See what each technology unlocks with color-coded indicators

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript**: No external dependencies required
- **Responsive Design**: Works on desktop and mobile devices
- **Data Source**: Based on official Civilization I game data
- **Open Source**: Feel free to contribute improvements or report issues

## 📊 Data Structure

The technology data is stored in a simple JavaScript object:

```javascript
{
  "Technology Name": {
    prereqs: ["Required Tech 1", "Required Tech 2"],
    allows: {
      units: ["Unit 1", "Unit 2"],
      buildings: ["Building 1"],
      wonders: ["Wonder 1"],
      other: ["Other Item"]
    }
  }
}
```

## 🚀 Local Development

To run this locally:

1. Clone the repository
2. Open `civ-tech-selector.html` in your web browser
3. That's it! No build process or dependencies required.

## 🤝 Contributing

Contributions are welcome! Some ideas:

- Add missing technologies or prerequisites
- Improve the UI/UX
- Add new features like tech tree visualization
- Fix any data inaccuracies

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

_Built with ❤️ for Civilization fans everywhere_
