# Civilization I Tech Planner

A modern, interactive web tool for planning technology research paths in Sid Meier's Civilization I. Plan your research strategy by selecting multiple target technologies and optimizing the research order.

## 🎮 Live Demo

**[Try it out here!](https://domaa11.github.io/civ1-tech-tree-advances-selector/)**

## ✨ Features

- **Multi-Target Planning**: Select multiple technologies as research targets
- **Smart Prerequisite Management**: Automatically combines prerequisites from all targets
- **Drag & Drop Reordering**: Optimize your research order with intuitive drag-and-drop
- **Automatic Dependency Reordering**: Smart algorithms maintain prerequisite integrity
- **Visual Technology Benefits**: Color-coded display showing what each technology unlocks:
  - 🟢 **Units** (Military units)
  - 🔵 **Buildings** (City improvements)
  - 🟣 **Wonders** (World wonders)
  - 🟡 **Other** (Governments, terrain improvements, etc.)
- **Search & Filter**: Find technologies quickly with real-time search
- **Save & Load Plans**: Save your optimized research paths for later reference
- **Validation System**: Real-time feedback on prerequisite completeness and order
- **Modern UI**: Clean, intuitive interface with smooth animations

## 🎯 How to Use

1. **Add Target Technologies**: Click "Add Technology Target" to select technologies you want to research
2. **Review Combined Prerequisites**: See all prerequisites needed for your selected targets
3. **Optimize Research Order**: Drag technologies to reorder them for optimal research efficiency
4. **Save Your Plan**: Save your optimized research path with a custom name
5. **Load Previous Plans**: Access your saved plans anytime

## 🚀 Key Features

### **Smart Multi-Target Support**

- Select multiple target technologies simultaneously
- Automatic prerequisite deduplication and combination
- Visual highlighting of target technologies in the research list

### **Intelligent Reordering**

- Drag-and-drop interface for easy reordering
- Automatic dependency validation
- Smart algorithms that maintain prerequisite integrity
- Two-way reordering: move prerequisites forward or dependents backward

### **Advanced Validation**

- Real-time prerequisite checking
- Order validation to ensure dependencies come first
- Clear visual feedback with color-coded status messages

### **Persistent Storage**

- Save multiple research plans
- Local storage for persistence across browser sessions
- Easy plan management with rename and delete options

## 🛠️ Technical Details

- **Modern Web Technologies**: HTML5, CSS3, JavaScript ES6+
- **No External Dependencies**: Pure vanilla JavaScript (except SortableJS for drag-and-drop)
- **Responsive Design**: Optimized for desktop and mobile devices
- **Progressive Enhancement**: Works without JavaScript for basic functionality
- **Data Source**: Complete Civilization I technology tree with accurate prerequisites
- **Open Source**: MIT licensed for community contributions

## 📊 Data Structure

The technology data uses a comprehensive structure:

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
2. Open `index.html` in your web browser
3. That's it! No build process or dependencies required.

## 🎨 UI/UX Highlights

- **Card-based Design**: Clean, modern interface with distinct functional areas
- **Visual Hierarchy**: Clear information architecture with logical flow
- **Smooth Animations**: Subtle transitions and hover effects
- **Accessibility**: High contrast, readable typography, keyboard navigation
- **Mobile Responsive**: Optimized layout for all screen sizes

## 🤝 Contributing

Contributions are welcome! Some ideas:

- Add new visualization features (tech tree graphs, timeline views)
- Improve the reordering algorithms
- Add export/import functionality for research plans
- Enhance the validation system
- Add support for different Civilization versions
- Improve mobile experience

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

_Built with ❤️ for Civilization fans everywhere_
