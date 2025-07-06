# 🧪 Physics Tools Streamlit App

A multi-page interactive **Streamlit application** for simulating and visualizing key physics concepts.  
Designed for students, educators, and science enthusiasts to explore physics through intuitive visual tools.

---

## 📦 Features

This app includes the following tools:

| Tool                          | Description |
|------------------------------|-------------|
| 🎯 **Projectile Motion**      | Simulate projectile motion by adjusting velocity, angle, and gravity. Shows trajectory and key metrics. |
| 🔍 **Lens Simulator**         | Visualize object and image positions for lenses. Calculates image distance, magnification, and type. |
| 🌊 **Wave Interference**      | Generate a double-slit interference pattern based on wavelength, screen distance, and slit separation. |
| ⚡ **RC Circuit Visualizer**  | Plot voltage vs. time for charging/discharging RC circuits with adjustable R, C, and voltage. |
| 🧠 **Quantum Wavefunction**   | View wavefunction and probability density for a particle in an infinite potential well (quantum box). |

---

## 🧰 Tech Stack

- [Python 3.8+](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/physics-tools-app.git
cd physics-tools-app
```
Install Dependencies
Create a virtual environment (optional) and install requirements:

```bash
pip install -r requirements.txt
```
If requirements.txt is missing:

```bash
pip install streamlit numpy matplotlib
```
3. Run the App
```bash
streamlit run main.py
```
Streamlit will open the app in your browser with sidebar navigation.

🗂️ Project Structure
```bash
physics-tools-app/
│
├── main.py                     # App dashboard with sidebar
├── pages/
│   ├── 1_Projectile_Motion.py
│   ├── 2_Lens_Simulator.py
│   ├── 3_Wave_Interference.py
│   ├── 4_RC_Circuit.py
│   └── 5_Quantum_Wavefunction.py
|--- requirements.txt
└── README.md
```

🎯 Projectile Motion

🔍 Lens Simulator

🌊 Wave Interference

## details
🧪 Educational Value
This project helps students:

Understand and visualize core physical phenomena

Perform virtual experiments

Explore "what-if" scenarios with parameter sliders

## 📚 License
MIT License © [Anurag Panda](https://github.com/anurag-panda-dev)
Feel free to fork and modify for personal or academic use.

## ✨ Contribute
Pull requests, bug reports, and suggestions are welcome!
Feel free to contribute your own physics visualizations as new pages.

## 🙏 Acknowledgements
Built using:

Streamlit

Physics formulas from standard high school and undergrad syllabi

🔗 Author
Anurag Panda
🔗 GitHub: @anurag-panda-dev
📧 Email: anuragpanda.dev@gmail.com
