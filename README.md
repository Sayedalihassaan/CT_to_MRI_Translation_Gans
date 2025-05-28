# 🧠 CT to MRI Translation Using Deep Learning

This project implements a deep learning pipeline for translating Computed Tomography (CT) images to Magnetic Resonance Imaging (MRI) scans using a convolutional neural network (CNN) architecture. This technique is relevant in medical imaging tasks where MRI is less accessible or CT offers limited information. The project showcases preprocessing, model training, evaluation, and visualization.

---

## 📂 Project Structure

- `Final_CT_to_MRI_Translation.ipynb` - The main notebook with all stages from data preparation to model inference.
- `data/` - Directory (not included) containing CT and MRI images.
- `models/` - Saved model checkpoints (if any).
- `outputs/` - Visual results of translated MRI images from CT inputs.

---

## 📌 Features

- Data preprocessing for 2D medical image slices
- CNN-based model architecture
- Image normalization and augmentation
- Training and validation loops
- Loss tracking and visualization
- MRI output generation and comparison
- Easily extendable for 3D data or GAN-based models

---

## 🧪 Requirements

Make sure to install the required Python packages:

```bash
pip install -r requirements.txt
````

Or install manually:

```bash
pip install numpy pandas matplotlib seaborn opencv-python scikit-learn tensorflow keras
```

---

## 🚀 Usage

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/ct-to-mri-translation.git
   cd ct-to-mri-translation
   ```

2. Prepare your dataset under a `data/` directory with paired CT and MRI images.

3. Open and run the notebook:

   ```
   Final_CT_to_MRI_Translation.ipynb
   ```

4. Monitor training performance and visualize outputs.

---

## 📈 Example Results

| Before (CT)                        | After (Predicted MRI)                 |
| ---------------------------------- | ------------------------------------- |
| ![CT Image](![IMG-0011-pt6](![IMG-0023-pt14](https://github.com/user-attachments/assets/8c58b067-2c32-4c3b-a8e3-5f3886bf079f)
) | ![MRI Output](![IMG-0023-pt14](https://github.com/user-attachments/assets/18512476-7b41-4ae3-a4ec-6efc68770a88)

---

## 🧠 Future Work

* Implement GANs (e.g., Pix2Pix or CycleGAN)
* Use 3D volume data instead of 2D slices
* Add metrics like SSIM, PSNR, and MAE for quantitative analysis

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**\[Your Name]**
[Your GitHub Profile](https://github.com/Sayedalihassaan)

---

## ⭐️ If you find this project useful, please give it a star on GitHub!
