# 😂 Meme Generator - Machine Learning Humor Edition

This is a fun and creative project where a meme image is programmatically generated using Python libraries like **Pillow** and **Matplotlib**. The meme humorously contrasts the pain of long training hours with the joy of hyperparameter tuning!

---

## 🖼️ Meme Theme

- **Top Text**:  
  *"Training a Model for 10 Hours\n\n Getting 55% Accuracy"*

- **Bottom Text**:  
  *"Hyperparameter Tuning \n\n Getting 95% Accuracy"*

---

## 🧰 Libraries Used

- `PIL` (Pillow): For image editing and text drawing
- `matplotlib`: For displaying the image inline

---

## 📝 How It Works

1. An image is loaded using `Image.open()`.
2. Custom font and size is applied using `ImageFont.truetype()`.
3. Two text boxes are drawn:
   - At the top: expressing frustration after training for hours.
   - At the bottom: celebrating the boost from hyperparameter tuning.
4. Image is displayed using `matplotlib.pyplot`.

