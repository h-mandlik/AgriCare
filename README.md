# AgriCare 🌱

A straightforward ML and DL-based website that offers recommendations on the best crops to grow, suitable fertilizers, and potential diseases affecting your crops.

---

## 📌 DISCLAIMER ⚠️

This project is a Proof of Concept (POC) and the data used is provided without any guarantees from the creator. It is not recommended for making real farming decisions. The creator will not be held responsible for any outcomes resulting from its use. However, this project demonstrates how ML/DL techniques can be leveraged for precision farming if scaled up with accurate and verified data.

---

## 🌾 Motivation

- Farming is one of the major sectors that influences a country’s economic growth.
- In a country like India, a large portion of the population depends on agriculture for their livelihood.
- With the advancement of technology, Machine Learning (ML) and Deep Learning (DL) are being increasingly applied in agriculture to help farmers improve yield and make informed decisions.
- This project aims to showcase how ML and DL can be integrated into agriculture through a web-based platform.

---

## 📌 Project Overview

This website demonstrates three key agricultural applications powered by ML/DL:

### 1. 🌱 Crop Recommendation
- The user inputs **soil data** (such as nitrogen, phosphorus, potassium, pH, etc.).
- The application predicts the **most suitable crop** to grow based on the input data.

### 2. 🌿 Fertilizer Recommendation
- The user provides **soil data** and the **type of crop** being cultivated.
- The system analyzes the nutrient composition and suggests:
  - What nutrients are **lacking or in excess**.
  - **Fertilizer recommendations** to improve soil health.

### 3. 🍂 Plant Disease Prediction
- The user uploads an **image of a diseased plant leaf**.
- The model:
  - Predicts the **disease affecting the plant**.
  - Provides a **brief description** of the disease.
  - Suggests **remedies or treatment methods**.

> ⚠️ **Note**: This is a Proof of Concept (POC) project. The data used is not verified and should **not** be used for real-life farming decisions. The creator holds **no responsibility** for any outcomes resulting from the use of this application.

---

## 📊 Data Sources

- [**Crop Recommendation Dataset**](https://www.kaggle.com/atharvaingle/crop-recommendation-dataset): Custom-built dataset tailored for predicting the best crop based on soil conditions.
- [**Fertilizer Suggestion Dataset**](https://github.com/Gladiator07/Harvestify/blob/master/Data-processed/fertilizer.csv): Custom-built dataset used to recommend suitable fertilizers based on soil nutrient levels and crop type.
- [**Disease Detection Dataset**](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset): Used for training a model that identifies plant diseases from leaf images.

---

## 💻 How to Use

### 🌱 Crop Recommendation System
- Input the **nutrient values** (N, P, K), **state**, and **city**.
- Note:
  - The N-P-K values should be provided as a **ratio**.
  - For accurate results, refer to soil testing reports or trusted agricultural resources.
  - When entering the city, prefer **major or commonly known city names**. Remote or less-known areas might not be supported by the weather API (used for temperature & humidity data).

### 🌿 Fertilizer Suggestion System
- Input:
  - **Soil nutrient content (N, P, K)**
  - **Crop name** (you intend to grow)
- Output:
  - The system will analyze if the soil has an **excess or deficiency** of specific nutrients.
  - Provides **fertilizer suggestions** to correct the imbalance.

### 🍂 Disease Detection System
- Upload a **leaf image** of the plant.
- The system will:
  - Predict the **crop type** and determine if the plant is **healthy or diseased**.
  - If diseased, it will:
    - Identify the **disease name**
    - Provide **background information**
    - Offer **suggestions for treatment and prevention**
- ⚠️ Currently, the system supports a limited set of crops (listed in the app interface).

---

## 🛠️ How to Run Locally

### 🔧 Prerequisites
- Install **Git**
- Install **Anaconda** or **Miniconda**

### 📥 Download/Clone the Repository
To get the latest deployment-ready code:
--link--

### 📂 Set Up Environment

Open Anaconda Prompt in the project directory.

Run the following commands:

```
conda create -n agricare python=3.6.12
conda activate agricare
pip install -r requirements.txt
```

### ▶️ Run the Project

```
python app.py
```

Open the localhost url provided after running app.py and now you can use the project locally in your web browser



---

## 🚀 Future Work

- Expand the **disease prediction model** to support more crops and disease types.
- Integrate **real-time satellite data** or **IoT sensor input** for enhanced precision.
- Build a **mobile-friendly version** of the platform for better accessibility.
- Add **multilingual support** to make the tool more inclusive for farmers across regions.
- Collaborate with agricultural experts to source **verified datasets** and improve model accuracy.

---

## 🤝 Contributing

Contributions are welcome!

If you'd like to improve this project, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/YourFeature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature/YourFeature`)
6. Open a Pull Request

For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- Thanks to open-source communities and developers whose tools and datasets helped build this POC.
- Special shoutout to the farmers and agri-tech pioneers inspiring innovation in the agriculture space.

---

## 🌟 Final Words

While this project is a **Proof of Concept**, it reflects the immense potential of integrating **Machine Learning** and **Deep Learning** into **agriculture**. With the right data and collaboration, we can build intelligent systems to help farmers make better, faster, and more informed decisions — paving the way for a smarter, more sustainable future in farming.

---

> Made with ❤️ for innovation in agriculture.
