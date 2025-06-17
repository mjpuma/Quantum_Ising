# Interactive Ising Model Visualizations

Interactive web-based visualizations for understanding classical and quantum Ising models in the context of trade policy networks.

## 🎯 Purpose

These visualizations were created to support research on quantum approaches to modeling global trade policy networks. They demonstrate how countries' trade policies (open vs. closed) can be modeled using Ising model physics, providing intuitive understanding of:

- Energy minimization in policy networks
- Coupling effects between countries
- External bias factors (institutional maintenance costs)
- Classical vs. quantum dynamics

## 📁 Files

- `classical_ising.html` - Interactive Classical Ising Model
- `quantum_ising.html` - Interactive Quantum Ising Model  
- `README.md` - This documentation

## 🚀 Quick Start

1. **Download** any HTML file
2. **Open** in your web browser (Chrome, Firefox, Safari, etc.)
3. **Interact** with the controls and grid
4. **No installation required** - everything runs in your browser

## 🧲 Classical Ising Model (`classical_ising.html`)

### Features
- **8×8 interactive grid** representing countries/regions
- **Real-time energy calculation** showing system stability
- **Parameter controls** for coupling (J) and external field (h)
- **Evolution animation** demonstrating energy minimization
- **Trade policy interpretation** with live feedback

### Controls
- **J (Coupling Strength)**: How countries influence each other
  - `J > 0`: Countries prefer same policies (coordination)
  - `J < 0`: Countries prefer opposite policies (competition)
- **h (External Field)**: Bias toward open/closed trade
  - `h > 0`: Bias toward closed trade (protectionism)
  - `h < 0`: Bias toward open trade (liberalization)

### How to Use
1. **Adjust parameters** using sliders
2. **Click grid squares** to flip individual policies
3. **Watch energy changes** in real-time
4. **Use "Evolve"** to see natural system evolution
5. **Try different scenarios** to build intuition

## ⚛️ Quantum Ising Model (`quantum_ising.html`)

### Features
- **Quantum superposition states** - policies can be in mixed states
- **Tunneling effects** - rapid policy transitions
- **Real-time quantum evolution** according to Schrödinger equation
- **Entanglement visualization** between coupled countries
- **Classical-quantum comparison** mode

### Additional Controls
- **Δ (Tunneling Rate)**: Quantum policy flexibility
- **Temperature**: Thermal vs. quantum effects
- **Evolution Type**: Classical, Quantum, or Mixed
- **Measurement**: Collapse superposition to definite states

## 🎓 Educational Applications

### For Students
- **Visualize abstract concepts** in statistical mechanics
- **Understand energy minimization** principles
- **See quantum effects** in macroscopic systems
- **Connect physics to social science** applications

### For Researchers
- **Parameter exploration** for model development
- **Intuition building** before data analysis
- **Presentation tool** for explaining methodology
- **Proof of concept** for quantum social science

### For Policymakers
- **Demonstrate trade interdependence** effects
- **Show institutional stability** factors
- **Visualize policy cascade** dynamics
- **Explain equilibrium** concepts

## 🔬 Research Context

These visualizations support research on:
- **Quantum approaches to trade policy modeling**
- **Institutional entropy and maintenance costs**
- **Policy cascade dynamics during crises**
- **Classical-to-quantum parameter mapping**

### Related Publications
[Add your papers/preprints here when available]

### Theoretical Framework
The models implement:
- **Classical Ising Hamiltonian**: `H = -J Σ σᵢσⱼ - h Σ σᵢ`
- **Quantum Ising Hamiltonian**: `H = E Σ σᶻ + Δ Σ σˣ + J Σ σˣσˣ`
- **Statistical mechanics equilibrium** calculations
- **Energy minimization** algorithms

## 🛠️ Technical Details

### Requirements
- **Modern web browser** (Chrome 80+, Firefox 75+, Safari 13+)
- **JavaScript enabled**
- **No additional dependencies** - pure HTML/CSS/JS

### Browser Compatibility
- ✅ **Chrome/Chromium** (recommended)
- ✅ **Firefox**
- ✅ **Safari**
- ✅ **Edge**
- ⚠️ **Internet Explorer** (not supported)

### Performance
- **Optimized for real-time interaction**
- **60 FPS animations** on modern hardware
- **Responsive design** for different screen sizes
- **Mobile-friendly** touch controls

## 📊 Example Use Cases

### Research Scenarios
```
Scenario 1: Cooperative Trade Bloc
- Set J = +2.0 (strong coordination)
- Set h = 0.0 (no bias)
- Watch aligned policy clusters form

Scenario 2: Trade War Dynamics  
- Set J = -1.0 (competitive dynamics)
- Set h = +1.0 (protectionist bias)
- Observe checkerboard anti-alignment

Scenario 3: Institutional Breakdown
- Start with stable configuration
- Gradually increase quantum tunneling (Δ)
- Watch coherent structures dissolve
```

### Teaching Examples
```
Physics Class: Energy Minimization
1. Show random initial state (high energy)
2. Run evolution (watch energy decrease)
3. Explain why system settles to stable state

Economics Class: Trade Interdependence
1. Set strong coupling (J = +2)
2. Flip one country's policy
3. Show cascade effect through network

Policy Class: Crisis Dynamics
1. Use quantum model with high Δ
2. Demonstrate rapid policy shifts
3. Compare to classical slow evolution
```

## 🤝 Contributing

Contributions welcome! Areas for improvement:
- **Additional visualization modes**
- **Export/import functionality**
- **More sophisticated quantum effects**
- **Multi-layer networks**
- **Real data integration**

### Development Setup
1. Clone repository
2. Open HTML files in browser
3. Edit with any text editor
4. Refresh browser to see changes

## 📄 License

MIT License - See LICENSE file for details

## 📞 Contact

mjp38@columbia.edu

## 🙏 Acknowledgments

- Built for quantum trade policy network research
- Inspired by statistical mechanics and international relations theory
- Uses vanilla JavaScript for maximum compatibility

---

**🔗 Quick Links:**
- [Classical Model](classical_ising.html) - Start here for basic concepts
- [Quantum Model](quantum_ising.html) - Advanced quantum effects
- [Research Context](#research-context) - Theoretical background
- [Use Cases](#example-use-cases) - Practical examples
