# 🧠 Text-to-Image Retrieval using CNN

This project enables users to retrieve the most relevant image from a dataset based on a natural language query. It uses Convolutional Neural Networks (CNNs) for visual feature extraction and NLP techniques for understanding user-provided text.

---

## 🚀 Features

- Retrieve best-matching image from a dataset using text queries.
- Uses pre-trained CNN for image embedding.
- Semantic understanding of text using text embeddings.
- Clean modular design, ready to extend.

---

## 📁 Folder Structure

```
Text-to-Image Retrieval using CNN/
├── model/                 # Model weights (not uploaded to GitHub)
├── Dataset/               # Image dataset and captions
├── TextToImage.py         # Main Python script
├── sample_inputs.txt      # Sample text prompts
├── requirements.txt       # Python dependencies
├── .gitignore
└── README.md
```

---

## 📦 Model & Dataset

### 🔗 Pre-trained Model

You can download the trained CNN model weights from the following Google Drive link:

👉 **[Download `gan_weights.hdf5` from Google Drive](https://drive.google.com/drive/folders/112i6j3XaZxi4hmU4uabxuolJQMr9zSZ7?usp=drive_link)**

> After downloading, place the file inside a folder named `model/` at the root of the project.

---

### 🖼️ Dataset Format

The dataset should contain:

- **Images** inside a `Dataset/` folder
- A `captions.txt` file formatted like this:

```txt
image1.jpg	A cat lying on the sofa
image2.jpg	A group of friends having dinner
image3.jpg	A boat sailing across the lake
```

Each image must be paired with a meaningful description.

---

## 🧪 How to Run

1. 📦 Install dependencies:
```bash
pip install -r requirements.txt
```

2. 🏁 Run the main script:
```bash
python TextToImage.py
```

3. ⌨️ Enter a text query like:
```
a dog running in the park
```

The system will return the most similar image from your dataset.

---

## 🛠️ Technologies Used

- Python 3
- TensorFlow / Keras
- NumPy, Pandas
- NLTK for text processing
- OpenCV / PIL for image loading

---

## ⚠️ Note

- The `model/` and `Dataset/` folders are ignored in GitHub using `.gitignore`.
- You must download the model weights and prepare the dataset locally.

---

