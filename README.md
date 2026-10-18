# PixelLab — NumPy Image Manipulation Toolkit

PixelLab is a Python project focused on understanding and manipulating digital images using **NumPy** and **Matplotlib**. It explores how images are represented as arrays and how pixels, RGB channels, and image regions can be processed using NumPy operations.

This project is part of my learning journey toward **AI/ML engineering**, with an emphasis on developing strong foundations in NumPy, image processing, and Python programming.

## 🎯 Project Goals

- Understand how digital images are represented as NumPy arrays.
- Learn to manipulate individual pixels and RGB channels.
- Practice array indexing, slicing, and Boolean masking.
- Perform basic image transformations using NumPy.
- Handle image data types and pixel-value limits safely.
- Build a foundation for future computer vision and image-based AI projects.

## ✨ Features and Concepts

- **Image basics:** Create and explore RGB images using NumPy arrays.
- **Pixel manipulation:** Access and modify individual pixels and image regions.
- **Cropping:** Extract image regions using array slicing.
- **Image flipping:** Flip images horizontally and vertically.
- **RGB channel extraction:** Separate and visualize red, green, and blue channels.
- **Brightness adjustment:** Brighten and darken images using NumPy.
- **Data type handling:** Work with `uint8`, integer conversion, and clipping.
- **Boolean masking:** Select pixels based on conditions and modify selected regions.
- **Image visualization:** Display images and compare results using Matplotlib.

## 🛠️ Technologies Used

- **Python** — programming language
- **NumPy** — array manipulation and image-processing operations
- **Matplotlib** — image visualization
- **Git and GitHub** — version control and project hosting

## 📁 Project Structure

```text
PixelLab/
│
├── notebooks/
│   ├── 01_image_basics_&_pixel_....ipynb
│   ├── 02_brightness_adjuster....ipynb
│   └── 03_boolean_masking.ipynb
│
├── src/
│   └── image_utils.py
│
├── .gitignore
├── main.py
├── README.md
└── requirements.txt
```

### Folder and file descriptions

| File or folder | Purpose |
|---|---|
| `notebooks/` | Jupyter notebooks for learning, experimenting, and demonstrating image-processing concepts. |
| `01_image_basics_&_pixel_....ipynb` | Experiments with image arrays, RGB values, pixels, slicing, and basic manipulation. |
| `02_brightness_adjuster....ipynb` | Practice with brightness adjustment, data types, and safe pixel-value handling. |
| `03_boolean_masking.ipynb` | Practice with Boolean masks and conditional pixel manipulation. |
| `src/` | Contains reusable Python code for the project. |
| `src/image_utils.py` | Module for reusable image-processing utility functions. |
| `main.py` | Main Python entry point for running the project. |
| `requirements.txt` | Lists the Python dependencies required by the project. |
| `.gitignore` | Specifies files and folders Git should ignore. |
| `README.md` | Project overview, setup instructions, features, and documentation. |

*Note: The notebook names above are shortened for readability. Replace them with the exact filenames if they differ in your repository.*

## 📦 Installation

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd PixelLab
```

Replace `<your-repository-url>` with your GitHub repository URL.

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it:

**macOS / Linux**

```bash
source .venv/bin/activate
```

**Windows**

```bash
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

## 🚀 Getting Started

You can explore the Jupyter notebooks in the `notebooks/` folder to learn and experiment with the image-processing operations.

For example, the following code creates and displays a simple RGB image:

```python
import numpy as np
import matplotlib.pyplot as plt

# Create a 100 × 100 RGB image
img = np.zeros((100, 100, 3), dtype=np.uint8)

# Fill the image with an RGB color
img[:, :] = [100, 150, 200]

# Display the image
plt.imshow(img)
plt.axis("off")
plt.show()
```

## 🧠 Learning Outcomes

Through PixelLab, I am developing practical skills in:

- NumPy arrays, indexing, slicing, and vectorized operations.
- RGB image representation and channel manipulation.
- Image cropping and flipping.
- Safe brightness adjustment and data type conversion.
- Boolean conditions and array masking.
- Visualizing image-processing results.
- Organizing code into reusable Python modules.

## 🗺️ Future Improvements

The following features are planned for future development:

- Add automated tests for image-processing functions.
- Improve input validation and error handling.
- Support loading and saving real JPG and PNG images.
- Expand reusable functions in `src/image_utils.py`.
- Add more image-processing operations.
- Build a web interface for interactive image manipulation.

## 📌 Current Project Scope

PixelLab is currently a learning-focused project centered on NumPy-based image manipulation and fundamental image-processing concepts.

It is not yet a machine learning model or a complete image-editing application. Its purpose is to strengthen the programming and array-manipulation skills needed for future computer vision and AI/ML projects.

## 📄 License

This project is intended to be released under the **MIT License**.

The MIT License permits use, modification, distribution, and commercial use, provided the required copyright and license notices are preserved.

See the [`LICENSE`](LICENSE) file for the full license terms.

**Important:** This section assumes you have added an actual `LICENSE` file containing the MIT license text to the repository. The README alone does not grant those permissions.

## 👨‍💻 Author & Contact

**Shreyas Vitthal Kumbhar**

If you have any questions, feedback, or want to collaborate on AI projects, feel free to reach out!

*   **GitHub:** [@Shreyask28](https://github.com/Shreyask28)
*   **LinkedIn:** [linkedin.com/in/shreyas-kumbhar-63715237a/](https://www.linkedin.com/in/shreyas-kumbhar-63715237a/)
*   **Email:** [kumbharshreyas7777@gmail.com](kumbharshreyas7777@gmail.com)

---
⭐ *If you find these tutorials helpful, please consider giving this repository a star!* ⭐
