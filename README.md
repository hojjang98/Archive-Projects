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

### 🔹 `bass_seeker`

- **Description**:  
  An audio-feature-based recommendation system designed to suggest *bass-heavy* songs by analyzing low-frequency energy rather than relying on conventional metadata like genre or artist.

- **Reason for Archival**:  
  During development, I realized that the **publicly accessible Spotify API** imposes heavy limitations on access to detailed audio features.  
  Additionally, I lacked sufficient **signal processing knowledge** to implement my own robust bass-detection algorithm from raw waveform data.  
  As a result, the project was paused until either higher-resolution data access becomes available or my understanding of audio analysis improves.

- **Takeaways**:
  - API access constraints can fundamentally limit ML system design.
  - A deeper understanding of domain-specific algorithms (e.g., spectral analysis) is necessary before building a production-quality audio recommender.

---

## 🔁 Possible Future Use

While these projects are not active, they may still be:
- Picked up later with better data or hardware
- Referenced for code reuse or experimental structure
- Converted into lighter prototypes

---

> 📝 These projects represent learning moments — even when unfinished.
