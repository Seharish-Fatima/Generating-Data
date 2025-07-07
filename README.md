# 🎲 Generating Data with Python: A Wild Ride Through Numbers, Chaos & Aesthetic Plots

Welcome to my data generation playground — where math meets magic and random numbers throw a party. This project is part coding practice, part creative chaos, and 100% powered by matplotlib, Plotly, and my villainous obsession with gradients 💅

## ✨ What This Project Does

This Jupyter Notebook explores various ways to generate, manipulate, and visualize data using Python. Think of it as a digital sketchbook of numerical experiments — featuring:
- Line plots
- Scatter plots
- Gradient scatter plots (yes, we’re fancy now)
- Dice roll simulations
- Interactive bar charts
- Random walks that would make Schrödinger proud

---

## 🧪 Tools I Played With

| Tool / Library      | What it did                              |
|---------------------|-------------------------------------------|
| `matplotlib.pyplot` | Basic (and not-so-basic) plotting         |
| `plotly.express`    | Interactive bar charts with ✨spice✨       |
| `numpy`             | Math on steroids                          |
| `random`            | For embracing chaos                       |
| `ScalarMappable`    | Color gradients that SLAY                 |
| `custom class`      | Like `RandomWalk` and `Die` to simulate behaviors |

---

## 📈 The Experiments

### 1. **Plotting Square Numbers**
We warmed up with a classic — plotting squares like a high school math nerd.  
> `input_values = [1, 2, 3, 4, 5]`  
> `squares = [1, 4, 9, 16, 25]`

We styled the plots with different `plt.style.use()` options — from `Solarize_Light2` to `_classic_test_patch` — and discovered how much plot personality we can pack in with just a theme change.

---

### 2. **Going Big: 1000+ Point Scatter Plots**
Next, we scaled up:  
```python
x_values = list(range(1, 1001))
y_values = [x**2 for x in x_values]
```
