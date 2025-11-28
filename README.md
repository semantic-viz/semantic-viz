## 🔎 Repository for the EvoStar Paper "Visualizations of the Semantic Space Exploration Performed by Ensemble Methods"

# ➡️ **[Click here to open the Interactive Dashboard](https://semantic-viz.github.io/semantic-viz/)**

Due to size restrictions, we could only upload 5 runs per dataset.


## Navigating 2D Plots

### Toolbar (Top Right)

| Icon | Name | Description |
|------|------|-------------|
| 📷 | Download | Save the plot as a PNG image |
| 🔍+ | Zoom | Click and drag to draw a rectangle to zoom into |
| ➕ | Pan | Click and drag to move around the plot |
| 🏠 | Reset Axes | Double-click anywhere or click this to reset to original view |
| ↔️ | Autoscale | Automatically fit all visible data |

### Mouse Controls

| Action | Effect |
|--------|--------|
| **Scroll wheel** | Zoom in/out centered on cursor |
| **Click + drag** | Depends on active tool (Zoom or Pan) |
| **Double-click** | Reset to original view |
| **Hover** | Show data point details (generation, RMSE, etc.) |

### Box Zoom (Default Tool)

1. Select the **Zoom** tool from the toolbar (magnifying glass icon)
2. Click and drag to draw a rectangle around the area of interest
3. Release to zoom into that region
4. Double-click to reset

### Panning

1. Select the **Pan** tool from the toolbar (cross arrows icon)
2. Click and drag to move the view
3. Useful when zoomed in to explore different regions

---

## Navigating 3D Plots

### Mouse Controls

| Action | Effect |
|--------|--------|
| **Left-click + drag** | Rotate the 3D scene (orbit around center) |
| **Right-click + drag** | Pan the scene (move camera position) |
| **Scroll wheel** | Zoom in/out |
| **Hover** | Show data point details |

### Toolbar (Top Right)

| Icon | Name | Description |
|------|------|-------------|
| 📷 | Download | Save as PNG |
| 🔄 | Orbital rotation | Default rotation mode |
| 🔃 | Turntable rotation | Rotate around vertical axis only |
| 🏠 | Reset camera | Return to default view angle |


---

## Legend Interactions

The legend (right side of plot) is **interactive**:

| Action | Effect |
|--------|--------|
| **Single-click** on legend item | Toggle visibility of that trace |
| **Double-click** on legend item | Isolate that trace (hide all others) |
| **Double-click** again | Show all traces |

## Trace Types

| Trace | Description |
|-------|-------------|
| **Target** | The optimization target (red star/diamond) |
| **Trees** | Individual trees from ensemble methods |
| **Model Trajectory** | Path of final best model across generations/iterations |
| **Best/Elite** | Final best model for each method |
| **Density Contours** | KDE density estimation of point distributions (2D only) |
| **RMSE Heatmaps** | Interpolated RMSE surface (2D only) |

---

## Tips

1. **Toggle off trees**: They can clutter the view; focus on trajectories first
2. **Use isolation**: Double-click legend items to compare methods one at a time
3. **Zoom to regions of interest**: Use box zoom in 2D or scroll in 3D
4. **Check RMSE on hover**: Every point shows its RMSE value
