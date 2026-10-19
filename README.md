# Orbit: ML in 3D

Machine learning math you can rotate, drag and break. Seven interactive 3D scenes built with Three.js, made as a companion to *Hands-On Machine Learning with Scikit-Learn and TensorFlow*.

**Live site:** https://YOUR-USERNAME.github.io/orbit-ml/

## Scenes

| Scene | What you can do | Book |
|---|---|---|
| Linear regression | Tilt a plane through 3D data, see residuals, solve the Normal Equation | Ch 4 |
| Gradient descent | Roll a ball down four loss surfaces; change learning rate and momentum | Ch 4, Ch 11 |
| Logistic regression | Shape a sigmoid probability sheet and its decision boundary, then fit it | Ch 4 |
| SVM kernel trick | Lift two rings into 3D so a flat plane can separate them | Ch 5 |
| PCA | Find principal axes and project a point cloud onto a line or plane | Ch 8 |
| K-Means | Step through assignment and centroid updates | Beyond the 1st edition |
| Neural network | Train a 2 → H → 1 network live and watch forward and backward passes | Ch 10, App. D |

## Run it

It's a single `index.html` with no build step. Open it in a browser, or serve the folder with any static host.

## Built with

- [Three.js](https://threejs.org/) r147 and OrbitControls
- Plain JavaScript; all the math (normal equation, gradient descent, eigen-decomposition, K-Means, backpropagation) is written from scratch in the page
