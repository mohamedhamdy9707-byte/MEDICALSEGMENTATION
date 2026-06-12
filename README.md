# 🏥 Medical Segmentation

![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![AI](https://img.shields.io/badge/AI-Deep%20Learning-brightgreen)
![Status](https://img.shields.io/badge/Status-Active-success)

> **Advanced Medical Image Segmentation using State-of-the-Art AI Models**

A comprehensive project for segmenting CT (Computed Tomography) images and identifying multiple organs using cutting-edge deep learning models. This project was developed by Cairo University students as part of their Systems and Biomedical Engineering curriculum.

---

## 🎯 Project Overview

This project focuses on **automatic organ segmentation** from CT scan images using advanced neural network architectures. The goal is to accurately identify and segment different organs in medical imaging, which has critical applications in:

- 📋 Clinical diagnosis
- 🔬 Treatment planning
- 📊 Medical research
- 🏥 Hospital automation

---

## 🚀 Features

✨ **Multiple AI Models:**
- Swin UNETR (Transformer-based architecture)
- TotalSegmentator (Comprehensive multi-organ segmentation)

🖼️ **CT Image Processing:**
- Multi-organ segmentation
- Support for various CT file formats
- Customizable organ selection

⚙️ **Easy to Use:**
- Jupyter Notebook interface
- Simple configuration
- Well-documented code blocks

---

## 📁 Project Structure

```
MEDICALSEGMENTATION/
├── README.md                                        # Project documentation
├── Swin_UNETR_BTCV_Multi_organ_Segmentation.ipynb  # Swin UNETR model implementation
├── totalsegmentator.ipynb                           # TotalSegmentator implementation
└── [data files]                                     # CT images and segmentation masks
```

---

## 📋 Requirements

Before running the notebooks, make sure you have:

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- Deep Learning frameworks (PyTorch, TensorFlow)
- Medical imaging libraries (SimpleITK, nibabel)
- NumPy, Pandas, Matplotlib

---

## 🔧 How to Use

### 1. **Setup Environment**
```bash
# Install required dependencies
pip install -r requirements.txt
```

### 2. **Run Notebooks**
```bash
jupyter notebook
```

### 3. **Choose Your Model**
- Open either `Swin_UNETR_BTCV_Multi_organ_Segmentation.ipynb` or `totalsegmentator.ipynb`
- Run the code blocks in sequence

### 4. **Customize Your Segmentation**
Edit the code blocks to:
- ✏️ Select your CT file
- 🎯 Choose which organs to segment
- 🔍 Adjust visualization parameters

### 5. **View Results**
The segmented organs will be displayed with color-coded masks for easy identification.

---

## 📚 Models Overview

### **Swin UNETR**
- Vision Transformer-based segmentation architecture
- Excellent performance on BTCV (Beyond the Cranial Vault) dataset
- Multi-organ capability

### **TotalSegmentator**
- Comprehensive segmentation model
- Supports 104+ anatomical structures
- Fast and efficient inference

---

## 👥 Contributors

| Name | GitHub |
|------|--------|
| **Mohamed Hamdy** | [@mhmdhamddyy](https://github.com/mohamedhamdy9707-byte) |
| **Mahmoud Mazen** | [@MahmoudMazen0](https://github.com/MahmoudMazen0) |
| **Ebrahim Nas** | [@ebrahimnas577](https://github.com/ebrahimnas577) |

---

## 👨‍🏫 Supervision

- **Prof. Dr. Tamer Basha** - Project Supervisor
- **Eng. Alaa Tarek** - Technical Advisor

---

## 🎓 Academic Context

This project was developed as a challenging task for first-year students in the **Department of Systems and Biomedical Engineering** at **Cairo University**. It serves as a practical introduction to:

- Medical image analysis
- Deep learning applications
- AI model implementation
- Clinical software development

---

## 📖 References & Resources

- [MONAI Framework](https://monai.io/) - Medical Open Network for AI
- [BTCV Dataset](https://www.synapse.org/#!Synapse:syn8291654/wiki/) - Beyond the Cranial Vault
- [Swin Transformer](https://github.com/microsoft/Swin-Transformer)
- [PyTorch Medical Imaging](https://pytorch.org/)

---

## 📝 License

This project is open-source and available for educational and research purposes.

---

## 💬 Support & Questions

For questions or issues, please:
1. Check the notebook documentation
2. Review code comments
3. Contact the project contributors

---

## ✅ Acknowledgments

Special thanks to:
- Cairo University Systems and Biomedical Engineering Department
- All contributors and supervisors
- The open-source medical AI community

---

**Made with ❤️ by Cairo University Biomedical Engineering Students**
