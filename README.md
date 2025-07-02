# Pitch type clustering

An unsupervised learning approach is proposed to handle the task of tagging pitch types in pitch-tracking data. This code will help you determine the actual pitch types of a single pitcher.

---

## Common issues with pitch type tagging

Use this code if:

- Tagger isn't tagging the pitch types correctly
- You don't know how many different pitch types the pitcher is actually throwing

---

### Example
t-SNE among other visualizations will help you get a feel of the number of pitch types
<img width="341" alt="image" src="https://github.com/user-attachments/assets/558d54f5-b9d4-4777-a865-84745630deba" />

Depending on how well-separated or balanced the data are, use k-means or DBSCAN to find the clusters
<img width="341" alt="image" src="https://github.com/user-attachments/assets/75aa6b77-64fc-4455-bb6c-58e6e0cfbdb5" />

After clusters are identified, use movement, velocity and spin rate to accurately name your pitches
<img width="557" alt="image" src="https://github.com/user-attachments/assets/d5dd5b7d-3a52-42d9-a8c8-ec100eac7a76" />


