<div style="
  margin-top: 10px;
  text-align: right;
  font-size: 0.9rem;
  background: white;
  padding: 10px 16px;
  border-radius: 10px;
  box-shadow: -2px 2px 6px rgba(0,0,0,0.2);
">
  <a href="./index" style="margin-right: 20px; text-decoration: none; color: #1a73e8; font-weight: bold;">🏠 Home</a>
  <a href="./publication" style="margin-right: 20px; text-decoration: none; color: #1a73e8; font-weight: bold;">📚 Publications</a>
  <a href="./ai4science" style="margin-right: 20px; text-decoration: none; color: #1a73e8; font-weight: bold;"> 🧠AI4Science</a>
  <a href="./physics" style="text-decoration: none; color: #1a73e8; font-weight: bold;"> 🌪️ PhysTransProcs</a>
</div>

<div style="margin-top: 40px;"></div>

<p align="center">
# 🌍 Climate Modeling with Generative AI
</p>

### 🔁 Probabilistic Climate Predictions

In machine learning weather assimilation, scientists use observations to adjust their models' trajectory and forecasts — like daily temperatures. This traditional method focuses on short-term accuracy. However, for **climate models**, it's essential to understand long-term dynamics and distributions, since we cannot replicate the exact future state of a single day.

This work proposes a new strategy to improve **data assimilation targeting statistical distributions**, looking beyond point forecasts to the broader range of likely states. It also introduces a **Bayesian framework** for **uncertainty-aware parameter inference**, enhancing projection reliability.

This approach enables better estimation of **extreme events** — like heatwaves or cold snaps — and analysis of their **joint quantile structures**.

📄 *Read more:*  
*Li, S.*, Zheng, T., Farchi, A., Bocquet, M., & Gentine, P. (2025). *Projections with generative machine learning: a Lorenz ’96 proof-of-concept.* *Geophysical Research Letters*, 52(12), e2024GL112523.

---

### 🛰️ Remote Sensing & Probabilistic Climate Projection

This research enhances climate forecasts by integrating **transport processes** into Earth System Models (ESMs). I utilize **indirect meteorological observations** — such as gas flux, vapor, and precipitation — via a **deep learning–based data assimilation framework** I designed.

Unlike traditional techniques bound by **linear/Gaussian assumptions**, my **multimodal framework** leverages **generative learning** to assimilate both **in-situ data** (e.g., CPC rain gauges) and **satellite remote sensing** (e.g., NOAA) under sparse, noisy conditions.

I further developed a **probabilistic data assimilation method** using **density-based modeling** for parameter inference and **Bayesian uncertainty quantification**, which is critical for **long-term projections** and for estimating the probability of major climate events like flooding and heat extremes.

📄 *Read more:*  
Qu, Y., Juan, N., *Li, S.*, & Gentine, P. (2024). *Deep generative data assimilation in multimodal setting.* In *CVPR Conference on Computer Vision and Pattern Recognition*, pp. 449–459.

---

### 🌊 Bridging Physics and Environment via AI

This work pioneers a **physics-informed ML framework** for modeling **suspended sediment transport** in vegetated flows. It enables **data-driven closure** of sediment dispersion fluxes, directly linking microscale turbulence to **bulk sediment concentration** in channel experiments.

Beyond sediment, I extend this approach to model **pier scour formation** using **machine learning–enhanced turbulence physics**. By unifying **TKE** and **shear stress budgets**, the model links **scour depth** to the dominant turbulent eddy scale — something previously inaccessible through traditional modeling.

Due to complexity, analytical solutions remain elusive. To overcome this, I apply **symbolic regression** to derive closed-form expressions linking **turbulent structures** with **geomorphic response** — opening new pathways for coupling **AI and physical sciences**.

📄 *Read more:*  
*Li, S.*, Qu, Y., Zheng, T., & Gentine, P. (2024). *Machine‐assisted physical closure for coarse suspended sediments in vegetated turbulent channel flows.* *Geophysical Research Letters*, 51(20), e2024GL110475.
