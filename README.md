# 🗃️ Archive Projects

This repository contains projects that were discontinued or paused mid-way.  
Although no longer under active development, these projects are kept for future reference or possible continuation.

They may contain:
- Partial code implementations,
- Experimental results,
- Learnings from real-world constraints (e.g., lack of data, hardware limitations).

---

## 📂 Archived Projects

### 🔹 `sales-forecasting_smallbiz`

- **Description**:  
  A time series and regression-based approach to forecast sales for small businesses, inspired by my family's chicken restaurant.

- **Reason for Archival**:  
  Although the project was nearly complete, I found that the dataset was too disconnected from real-world sales patterns.  
  Most available public data lacked granularity and had many missing values.  
  In reality, accurate modeling would require access to private credit card transaction records or point-of-sale data, which are not publicly available.

- **Takeaways**:
  - Feature engineering was challenging due to missing values and data noise.
  - Modeling can only be as good as the data — domain alignment is critical.

---

### 🔹 `urban-scene-segmentation`

- **Description**:  
  A semantic segmentation project on urban scene images, aimed at understanding road environments.

- **Reason for Archival**:  
  The project could not proceed due to hardware limitations — my local setup was not capable of handling high-resolution training at scale.

- **Takeaways**:
  - Segmentation tasks are resource-intensive; scaling up requires either cloud computing or a powerful local GPU.
  - Labeling complexity and memory bottlenecks are serious considerations in vision tasks.

---

## 🔁 Possible Future Use

While these projects are not active, they may still be:
- Picked up later with better data or hardware
- Referenced for code reuse or experimental structure
- Converted into lighter prototypes

---

> 📝 These projects represent learning moments — even when unfinished.
