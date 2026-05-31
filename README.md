# 🎨 Canvas Border Calculator & Image Grid Overlay Studio

A powerful, user-friendly web application combining professional canvas border calculations with advanced image grid overlay tools. Perfect for artists, designers, and photographers!

---

## ✨ Features

### 🎨 Canvas Border Calculator
- **Multiple Unit Support**: Calculate in cm, inches, feet, or meters
- **Real-time Calculations**: Instant results as you type
- **Auto Unit Conversion**: Switch units and all values convert automatically
- **Formula Display**: See the exact calculation formulas
- **Conversion Tables**: Quick reference for different units
- **Beautiful Results**: Color-coded result cards with highlights

### 🖼️ Image Grid Overlay Tool
- **Advanced Grid System**:
  - Default Grid (center lines, diagonals, diamond, quarter guides)
  - Custom Grid (adjustable horizontal/vertical divisions)
  - Diagonal Subdivisions with smart clipping
  - Diamond Guide overlay

- **Customization Options**:
  - Adjustable line color and width
  - Control grid opacity
  - Configurable scale multiplier
  - Toggle rulers on/off

- **Professional Features**:
  - Accurate rulers with automatic tick spacing
  - Real-time preview of grid overlay
  - Download with or without rulers
  - Export as PNG or JPG

---

## 🚀 Quick Start

### Installation
Simply download the HTML file and open it in any modern web browser. No server or dependencies required!

```bash
# Option 1: Direct download and open
# Download combined_canvas_tools.html and double-click to open

# Option 2: Use with a local server (optional)
python -m http.server 8000
# Then visit: http://localhost:8000/combined_canvas_tools.html
```

### Browser Compatibility
- ✅ Chrome/Chromium (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera

---

## 📖 How to Use

### **Tab 1: Canvas Border Calculator**

1. **Select Unit**: Choose your preferred measurement unit (cm, inch, feet, meters)
2. **Enter Dimensions**: 
   - Input your artwork width
   - Input your artwork height
   - Specify border width (applies to all sides)
3. **Calculate**: Click the "Calculate" button
4. **View Results**:
   - Original artwork dimensions
   - Border width
   - **Final canvas size with borders**
5. **Convert**: Switch units anytime - all values update automatically
6. **Reset**: Clear all fields and start over

**Example:**
- Artwork: 20cm × 30cm
- Border: 2cm
- Result: 24cm × 34cm canvas

---

### **Tab 2: Image Grid Overlay**

1. **Upload Image**: 
   - Click to browse or drag & drop an image
   - Supports JPG, PNG, GIF, WebP, etc.

2. **Configure Grid**:
   - **Grid Type**: Choose your grid style
     - Default Grid: Professional center lines and guides
     - Custom Grid: Set exact number of divisions
     - Diagonal: Perfect for composition
     - Diamond: Unique artistic guide

3. **Customize Appearance**:
   - **Line Color**: Pick any color for your grid
   - **Line Width**: Adjust thickness (1-10px)
   - **Opacity**: Control visibility (0-100%)
   - **Scale Multiplier**: Enlarge grid (0.5x - 3x)

4. **Add Measurements**:
   - Toggle rulers on/off
   - Choose ruler position and unit
   - Auto-calculated tick spacing

5. **Preview**: See real-time preview of your grid

6. **Download**:
   - Choose format (PNG or JPG)
   - Option to include/exclude rulers
   - Click "Download" to save

---

## 🎯 Use Cases

### For Artists & Illustrators
- Calculate canvas sizes for stretched frames
- Plan composition using grid overlays
- Maintain proper proportions with grids

### For Photographers
- Analyze composition with rule of thirds
- Plan framing before shooting
- Edit images with professional grids

### For Designers & Architects
- Calculate border dimensions accurately
- Overlay grids for precise measurements
- Export reference images with measurements

### For Crafters & Framing
- Determine mat and frame sizes
- Calculate multiple border options
- Get instant unit conversions

---

## 🛠️ Technical Details

### Built With
- **Pure HTML5**: No frameworks required
- **CSS3**: Modern styling with gradients and animations
- **Vanilla JavaScript**: No dependencies
- **Canvas API**: For grid rendering
- **File API**: For image handling

### File Size
- Single HTML file (~80 KB)
- No external dependencies
- Instant loading
- Works offline

### Performance
- Real-time calculations
- Smooth animations (60fps)
- Optimized for all devices
- Responsive design

---

## 🎨 Customization

### Changing Colors
Edit the CSS variables in the `<style>` section:

```css
:root {
  --primary: #4f46e5;        /* Main color */
  --secondary: #10b981;      /* Accent color */
  --bg: #f8fafc;             /* Background */
  --card: #ffffff;           /* Card background */
  /* ... more variables ... */
}
```

### Adjusting Sizing
Modify the font sizes and spacing:

```css
header h1 {
  font-size: 3rem;           /* Change header size */
}

.card {
  padding: 32px;             /* Change card padding */
}
```

---

## 💡 Tips & Tricks

### Canvas Calculator
- ✅ Use "cm" for metric work
- ✅ Use "inch" for US standards
- ✅ Tab between fields for quick entry
- ✅ Copy results for use in other applications
- ✅ Unit conversion happens automatically!

### Grid Overlay
- ✅ Start with default grid for best results
- ✅ Use lower opacity (30-50%) for subtle grids
- ✅ White or light colors work best for dark images
- ✅ Black or dark colors for light images
- ✅ Export as PNG to preserve transparency
- ✅ Use rulers for professional documentation

### Best Practices
- ✅ Save originals before adding grids
- ✅ Test different grid types on your image
- ✅ Use 2-3px line width for clarity
- ✅ Keep opacity between 30-60% for visibility
- ✅ Export at high resolution for printing

---

## 📱 Responsive Design

Works perfectly on all devices:

| Device | Support |
|--------|---------|
| Desktop (1200px+) | ✅ Full features |
| Tablet (768px-1200px) | ✅ Optimized layout |
| Mobile (< 768px) | ✅ Single column |

The interface automatically adapts to your screen size!

---

## 🔒 Privacy & Security

- ✅ **100% Local Processing**: All calculations happen in your browser
- ✅ **No Server**: Nothing is uploaded or stored
- ✅ **No Tracking**: Complete privacy
- ✅ **Works Offline**: No internet required after initial load

---

## 🐛 Troubleshooting

### Image not loading?
- Check file format (JPG, PNG, GIF, WebP supported)
- Ensure file is not corrupted
- Try a different image

### Grid not showing?
- Increase line width (try 2-3px)
- Adjust opacity (try 50-80%)
- Check grid color is visible on image

### Calculation seems wrong?
- Verify unit selection matches your needs
- Double-check input values
- Clear fields and recalculate

### Download not working?
- Check browser download settings
- Try a different export format
- Clear browser cache

---

## 📊 Grid Type Guide

| Grid Type | Best For | Use Case |
|-----------|----------|----------|
| **Default** | Professional work | General design, reference |
| **Custom** | Specific divisions | Technical drawings, grids |
| **Diagonal** | Composition | Photography, artwork |
| **Diamond** | Artistic guides | Creative work, planning |

---

## 🎓 Learning Resources

### Composition Tips
- Learn the **rule of thirds** for balanced composition
- Use **golden ratio** for natural-looking designs
- **Diagonal lines** guide viewer's eye
- **Center guides** help with symmetry

### Unit Conversions
```
1 meter = 100 cm = 39.37 inches = 3.28 feet
1 inch = 2.54 cm
1 foot = 30.48 cm = 12 inches
```

---

## 🙌 Credits

Designed and developed with ❤️ for creative professionals.

### Technologies Used
- HTML5 Canvas API
- CSS3 Flexbox & Grid
- Vanilla JavaScript ES6+

---

## 📝 License

This tool is provided as-is for personal and professional use.

---

## 🚀 Future Enhancements

Potential features for future versions:
- Batch processing for multiple images
- Custom grid templates
- Save/load presets
- Undo/Redo functionality
- Advanced measurement tools
- Export to PDF with annotations

---

## 💬 Feedback

Enjoy using Canvas Border Calculator & Grid Overlay Studio!

For best experience:
- Keep browser updated
- Use Chrome or Firefox
- Test with sample images first
- Export in PNG for quality preservation

---

## 🌟 Quick Reference

### Keyboard Shortcuts (Future)
- `Ctrl+Z` - Undo
- `Ctrl+S` - Save
- `Enter` - Calculate

### File Formats
- **Input**: JPG, PNG, GIF, WebP, BMP
- **Output**: PNG (recommended), JPG

### Measurement Units
- Centimeter (cm)
- Inch (in)
- Meter (m)
- Feet (ft)

---

**Made with ❤️ for creators, artists, and designers worldwide.**

*Last Updated: May 2026*
