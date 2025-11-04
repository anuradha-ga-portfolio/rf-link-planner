A web-based tool that allows users to plan simple point-to-point RF links between towers on a map
Built with Leaflet.js, HTML, CSS, and Vanilla JavaScript

Live demo on
👉 [https://rf-link-planner-omega.vercel.app/](https://rf-link-planner-omega.vercel.app/)  

Features:

- Click on map to place towers  
- Edit tower frequency (GHz or MHz)  
- Connect towers only if frequencies match  
- Show link distance and frequency info  
- Click a link to visualize the First Fresnel Zone (simplified ellipse)  
- Remove or reconfigure towers/links  
- Responsive for desktop & tablet

- Fresnel Zone Formula:
  \[
  r = \sqrt{ \frac{λ \cdot d1 \cdot d2}{d1 + d2} }, \quad λ = \frac{3×10^8}{f}
  \]
- Elevation (optional): can use [Open-Elevation API](https://open-elevation.com/)


1. Clone the repo  
   ```bash
   git clone https://github.com/anuradha-ga-portfolio/rf-link-planner.git
