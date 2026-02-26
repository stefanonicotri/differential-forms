# Differential Forms & Vector Calculus

A comprehensive, interactive web guide that bridges the gap between classical 3D vector calculus, differential geometry, and the foundations of theoretical physics. 

This project provides a rigorous, step-by-step mathematical breakdown of how the standard vector operators (Gradient, Curl, and Divergence) emerge from the deeper, more generalized language of differential forms.

## 📖 Overview

In classical mechanics, electromagnetism, and fluid dynamics, vector calculus is the standard language. However, when scaling up to $n$-dimensions or mapping out the fabric of 4D spacetime, classical vectors fall short. This project explores how the exterior derivative, musical isomorphisms, and the Hodge star operator unify these concepts elegantly.

### Mathematical Topics Covered
* **Deriving the Big Three:** Step-by-step derivations translating the Gradient, Curl, and Divergence into 0-forms, 1-forms, 2-forms, and 3-forms.
* **The Hodge Star Operator:** Understanding the mapping between dimensions and the geometric implications of the double Hodge star.
* **N-Dimensional Generalizations:** Why the Gradient and Divergence scale perfectly, but the Curl inherently fails to be a vector field in higher dimensions.
* **Electromagnetism in Spacetime:** Collapsing Maxwell's four interlocked equations into two elegant differential forms statements.
* **Gauge Invariance:** A mathematical proof showing how the topological rule of the exterior derivative guarantees gauge invariance.
* **Boundary of a Boundary:** Bridging algebraic topology and geometry via the Generalized Stokes' Theorem to prove why closed shapes have no edges.

## ✨ Technical Features

This project is built as a lightweight, highly optimized single-page application (SPA) contained entirely within a single HTML file.

* **On-the-fly LaTeX Rendering:** Utilizes [MathJax 3](https://www.mathjax.org/) to natively render complex differential geometry equations and matrices directly in the browser.
* **Fully Responsive Design:** CSS styling is built with CSS variables and system fonts to ensure mathematical derivations are readable on any device size.
* **Persistent Dark Mode:** Includes a vanilla JavaScript toggle that seamlessly flips the UI and SVG-based MathJax text between Light and Dark themes, saving the user's preference to `localStorage`.
* **Zero Dependencies:** No external CSS frameworks or heavy JS libraries (other than MathJax) are required. 


## 📄 License

This work is licensed under a Creative Commons Attribution-NonCommercial 4.0 International License.
