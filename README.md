# 🧬 FEPS: Feature Extraction from Protein Sequences

**FEPS** is a comprehensive web-based bioinformatics tool designed to extract the most widely used **sequence-derived features** from protein sequences. 

Pioneering the field of automated protein feature extraction, **FEPS** was first released in **2016** and has since evolved into a powerful platform supporting both traditional **machine learning** and modern **deep learning** approaches.

[![DOI](https://img.shields.io/badge/DOI-10.1007%2F978--1--0716--2317--6__3-blue)](https://doi.org/10.1007/978-1-0716-2317-6_3)

---

## 🔍 Key Features

- **48** distinct feature extraction methods  
- Organized into **7 major feature groups**  
- Computes a total of **2765 descriptors**  
- Supports multiple input groups and class labels  
- Direct integration with ML/DL pipelines (SVM, RF, KNN, CNN, etc.)  
- Designed for scalability, reproducibility, and usability  

📖 *Ismail et al., 2022 — [FEPS: A Tool for Feature Extraction from Protein Sequence](https://doi.org/10.1007/978-1-0716-2317-6_3)*

---

## 🎯 Applications

FEPS-generated features can be used for a wide range of classification and prediction tasks in computational biology, such as:

- 🧠 Protein function prediction  
- 🧬 Protein classification  
- 🧱 Protein structure prediction  
- 📍 Subcellular localization prediction  
- ➕ And many more!

---

## 🌐 Access the Webserver

👉 Launch the FEPS tool: [https://hdismail.com/feps/](https://hdismail.com/feps/)

---

## 📥 Input Format

FEPS accepts **fasta-formatted protein sequence files**. The recommended format for classification scenarios:

- ✅ Sequences **must be valid protein sequences**
- ✅ Files must be in **FASTA format**
- ✅ Sequences **of the same class/group** should be combined into one file
- ✅ The **filename** will be used to label the group

📦 [Download example dataset](https://hdismail.com/media/tutorial.zip)

> 💡 *Replace `your-username/your-repo-name` with the actual GitHub repo path.*

---

## 🧾 Feature Types

The extracted features are organized into **7 major groups**:

| Group | Feature Category |
|-------|------------------|
| 1     | Amino Acid Composition |
| 2     | Composition, Transition, and Distribution |
| 3     | Autocorrelation Descriptors |
| 4     | Pseudo Amino Acid Composition |
| 5     | Quasi & Sequence-Order-Coupling |
| 6     | Shannon Entropy Descriptors |
| 7     | Conjoint Triad |

Users can interactively select any group and corresponding methods using the web interface.

---

## 🚀 Getting Started

👉 Visit the FEPS Webserver: [https://hdismail.com/feps/](https://hdismail.com/feps/)  
👉 Read the full article: [Methods in Molecular Biology, 2022](https://doi.org/10.1007/978-1-0716-2317-6_3)  
👉 [Download example dataset](https://github.com/your-username/your-repo-name/raw/main/example_dataset.zip)

---

## 📄 Citation

If you use FEPS in your research, please cite:

> Ismail H, White C, Al-Barakati H, Newman RH, Kc DB. (2022). **FEPS: A Tool for Feature Extraction from Protein Sequence.** *Methods Mol Biol.* 2499:65–104. https://doi.org/10.1007/978-1-0716-2317-6_3

---

## 🧑‍💻 Authors

- **Dr. Hamid D. Ismail**  
- Collaborators: White C, Al-Barakati H, Newman RH, Kc DB

---

## 📬 Contact

For questions or feature requests, please contact:  
📧 [hamid@hamiddi.com](mailto:hamid@hamiddi.com)

---

## 📘 License

This project is licensed under the [MIT License](LICENSE).
