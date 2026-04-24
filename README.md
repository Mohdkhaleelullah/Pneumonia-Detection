
### 🫁 Pneumonia Detection from Chest X-rays

This project applies deep learning techniques to classify chest X-ray images as either **Pneumonia** or **Normal (Healthy)**. It utilizes **transfer learning** with a fine-tuned convolutional neural network to achieve high accuracy in detecting pneumonia from radiographic images.

---

### 📊 Dataset

The dataset contains labeled chest X-ray images categorized into two classes:

* **Pneumonia**
* **Normal (Healthy)**

To ensure reliable model evaluation, the data is divided into three subsets:

* Training set
* Validation set
* Test set

---

### ⚙️ How to Use

1. Clone this repository
2. Organize the dataset into the following directories:

   * `train/`
   * `val/`
   * `test/`
3. Open the `pneumonia.ipynb` notebook using Google Colab or Jupyter Notebook
4. Execute all cells to train and evaluate the model

---

### 🧰 Requirements

* Python 3.x
* PyTorch
* torchvision
* scikit-learn
* NumPy

Install the required dependencies using:

```bash
pip install torch torchvision scikit-learn numpy
```
