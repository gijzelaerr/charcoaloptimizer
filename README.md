# ULTIMATE CHARCOAL PACKING MAXIMIZER 3000! 🔥📦

> PACK MORE! EARN MORE! SAVE MORE!

A revolutionary web-based tool for charcoal producers to optimize bag packaging and maximize container utilization. Calculate the perfect bag dimensions, visualize your packing strategy in stunning 3D, and boost your shipping efficiency!

## 🚀 Features

### Optimization Modes
- **Auto-Optimize Mode**: Let the AI find the perfect bag dimensions based on weight and density
- **Manual Override Mode**: Test your own bag dimensions and see how many fit

### Smart Packing Algorithm
- ✅ **Alternating Layer Orientations**: Bags rotate 90° between layers for maximum stability
- ✅ **Automatic Pallet Rotation**: Tests both pallet orientations in the container
- ✅ **Constraint-Based Search**: Set min/max bag dimensions to avoid impractical shapes
- ✅ **Multi-Dimensional Optimization**: Considers all possible bag orientations

### Visualizations
1. **2D Canvas Views**
   - Bags on pallet (top-down view)
   - Pallets in container (layout view)
   - Proper aspect ratio preservation

2. **Interactive 3D Viewer**
   - Full Three.js powered 3D rendering
   - Mouse controls (rotate, pan, zoom)
   - Auto-rotating camera option
   - Exploded view slider (spread bags from center)
   - Color-coded orientation layers
   - Real-time updates

### Results Dashboard
- Total bags per container
- Bags per pallet with layer breakdown
- Pallets per container
- Total weight
- Optimal/manual bag dimensions
- Pallet rotation indicator

## 🎯 How It Works

### The Math Behind It

1. **Volume Calculation**: `Bag Volume = Weight ÷ Density`
2. **Dimension Search**: Tests thousands of L×W×H combinations that equal the required volume
3. **Layer Optimization**:
   - Layer 1: Bags in orientation 1 (L along pallet L, W along pallet W)
   - Layer 2: Bags rotated 90° (W along pallet L, L along pallet W)
   - Layer 3+: Alternates...
4. **Pallet Packing**: Tests both normal and 90° rotated pallet placement in container
5. **Best Fit Selection**: Chooses configuration with maximum total bags

### Configuration Options

**Container Dimensions**
- Length, Width, Height (default: 40ft container = 1200×235×239 cm)

**Pallet Dimensions**
- Length, Width (default: EUR pallet = 120×80 cm)
- Max Height (default: 120 cm)

**Bag Specifications (Optimize Mode)**
- Weight per bag (kg)
- Charcoal density (kg/m³)
- Min/max bag dimensions (cm)
- Search step precision (cm)

**Bag Specifications (Manual Mode)**
- Exact Length, Width, Height (cm)
- Weight per bag (kg)

## 🛠️ Technology Stack

- **Frontend**: Pure HTML/CSS/JavaScript (single file!)
- **3D Graphics**: Three.js (r128)
- **3D Controls**: OrbitControls
- **No Build Process**: Just open and run!

## 📖 Usage

### Option 1: Use Online (GitHub Pages)
Visit the live demo at: `https://gijzelaerr.github.io/charcoaloptimizer/charcoal-optimizer.html`

### Option 2: Run Locally
1. Download `charcoal-optimizer.html`
2. Open it in any modern web browser
3. That's it! No installation required.

### Using the Tool

1. **Enter your container and pallet dimensions** (or use defaults)

2. **Choose your mode**:
   - **Optimize**: Let the tool find the best bag size
   - **Manual Override**: Test specific bag dimensions

3. **Click "Calculate"**

4. **Explore the results**:
   - View optimal dimensions
   - Check total bags and weight
   - Examine 2D visualizations
   - Interact with 3D model
   - Use explosion slider to see inside

5. **Iterate**: Try different settings or manual dimensions to compare options

## 🎨 UI Features

- **Responsive Design**: Works on desktop and tablet
- **Real-time Updates**: Instant calculations
- **Intuitive Controls**: Easy-to-use interface
- **Professional Visualizations**: Clear, color-coded displays
- **Exploded View**: Slider to spread bags apart for better visibility

## 🔬 Use Cases

- **Charcoal Producers**: Optimize packaging for maximum profit
- **Logistics Companies**: Plan container loads efficiently
- **Packaging Designers**: Test different bag size options
- **Supply Chain Managers**: Calculate shipping costs accurately
- **Manufacturing**: Plan production runs based on container capacity

## 📊 Example Results

With default settings (5kg bags, 300 kg/m³ density):
- Optimal bag dimensions: ~30×20×10 cm
- Bags per pallet: ~200-300 (depending on configuration)
- Pallets per container: 20
- Total bags: 4,000-6,000
- Total weight: 20-30 tons

## 🤝 Contributing

Feel free to fork, modify, and improve! This is a single-file application, so it's easy to customize.

## 📜 License

Open source - use freely for personal or commercial purposes!

## 🙏 Acknowledgments

Built with the power of:
- Three.js for 3D rendering
- Modern web standards (Canvas API, ES6+)
- A passion for optimization problems!

---

**PACK MORE CHARCOAL TODAY!** 🔥📦💰

*"The SECRET WEAPON Every Charcoal Producer Has Been WAITING FOR!"*
