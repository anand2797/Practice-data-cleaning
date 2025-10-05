<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">

<img src="readmeai/assets/logos/purple.svg" width="30%" style="position: relative; top: 0; right: 0;" alt="Project Logo"/>

# <code>KIDNEY DISEASE CLASSIFICATION</code>

<em></em>

<!-- BADGES -->
<!-- local repository, no metadata badges. -->

<em>Built with the tools and technologies:</em>


</div>
<br>

---

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
    - [Project Index](#project-index)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Usage](#usage)
    - [Testing](#testing)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## Overview
- This project focuses on predicting kidney disease using machine learning models. 
- It includes data cleaning, preprocessing, and model training steps, along with serialized models for prediction. 
- The project is implemented primarily in Python and Jupyter notebooks.



---


## Features

The dataset contains the following features for predicting kidney disease:

- <code>id</code> – Unique identifier for each patient.
- <code>age</code> – Age of the patient in years.
- <code>bp</code> – Blood pressure (mm/Hg).
- <code>sg</code> – Specific gravity of urine.
- <code>al</code> – Albumin level in urine.
- <code>su</code> – Sugar level in urine.
- <code>rbc</code> – Red blood cells (normal/abnormal).
- <code>pc</code> – Pus cell (normal/abnormal).
- <code>pcc</code> – Pus cell clumps (present/notpresent).
- <code>ba</code> – Bacteria (present/notpresent).
- <code>bgr</code> – Blood glucose random (mg/dL).
- <code>bu</code> – Blood urea (mg/dL).
- <code>sc</code> – Serum creatinine (mg/dL).
- <code>sod</code> – Sodium level (mEq/L).
- <code>pot</code> – Potassium level (mEq/L).
- <code>hemo</code> – Hemoglobin (gms).
- <code>pcv</code> – Packed cell volume (%).
- <code>wc</code> – White blood cell count.
- <code>rc</code> – Red blood cell count.
- <code>htn</code> – Hypertension (yes/no).
- <code>dm</code> – Diabetes mellitus (yes/no).
- <code>cad</code> – Coronary artery disease (yes/no).
- <code>appet</code> – Appetite (good/poor).
- <code>pe</code> – Pedal edema (yes/no).
- <code>ane</code> – Anemia (yes/no).
- <code>classification</code> – Target variable (ckd/notckd).

This dataset combines **demographic, clinical, and laboratory data** to predict the presence of chronic kidney disease.


---

## Project Structure

```sh
└── Kidney Disease Classification From Kaggle/
    ├── kidney.xlsx
    ├── kidney_disease.csv
    ├── kidney_disease_cleaned_data.csv
    ├── kidney_disease_data_cleaning.ipynb
    ├── kidney_disease_practice_data_cleaning.ipynb
    ├── kidney_disease_logistic_mm.pkl
    ├── kidney_disease_logistic_std.pkl
    ├── kidney_disease_svm_std.pkl
    ├── README.md
    ├── project_tree.txt
    └── .ipynb_checkpoints/
```


### Project Index

<details open>
	<summary><b><code>/</code></b></summary>
	<!-- __root__ Submodule -->
	<details>
		<summary><b>__root__</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ __root__</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
			<tr style='border-bottom: 1px solid #eee;'>
				<td style='padding: 8px;'><b><a href='/kidney.xlsx'>kidney.xlsx</a></b></td>
				<td style='padding: 8px;'>Original dataset in Excel format</td>
			</tr>
			<tr style='border-bottom: 1px solid #eee;'>
				<td style='padding: 8px;'><b><a href='/kidney_disease.csv'>kidney_disease.csv</a></b></td>
				<td style='padding: 8px;'>Raw CSV version of the dataset</td>
			</tr>
			<tr style='border-bottom: 1px solid #eee;'>
				<td style='padding: 8px;'><b><a href='/kidney_disease_cleaned_data.csv'>kidney_disease_cleaned_data.csv</a></b></td>
				<td style='padding: 8px;'>Cleaned dataset after preprocessing</td>
			</tr>
			<tr style='border-bottom: 1px solid #eee;'>
				<td style='padding: 8px;'><b><a href='/kidney_disease_data_cleaning.ipynb'>kidney_disease_data_cleaning.ipynb</a></b></td>
				<td style='padding: 8px;'>Notebook for data cleaning and preprocessing</td>
			</tr>
			<tr style='border-bottom: 1px solid #eee;'>
				<td style='padding: 8px;'><b><a href='/kidney_disease_practice_data_cleaning.ipynb'>kidney_disease_practice_data_cleaning.ipynb</a></b></td>
				<td style='padding: 8px;'>Additional notebook for practicing data cleaning</td>
			</tr>
			<tr style='border-bottom: 1px solid #eee;'>
				<td style='padding: 8px;'><b><a href='/kidney_disease_logistic_mm.pkl'>kidney_disease_logistic_mm.pkl</a></b></td>
				<td style='padding: 8px;'>Serialized Logistic Regression model with Min-Max scaling</td>
			</tr>
			<tr style='border-bottom: 1px solid #eee;'>
				<td style='padding: 8px;'><b><a href='/kidney_disease_logistic_std.pkl'>kidney_disease_logistic_std.pkl</a></b></td>
				<td style='padding: 8px;'>Serialized Logistic Regression model with standard scaling</td>
			</tr>
			<tr style='border-bottom: 1px solid #eee;'>
				<td style='padding: 8px;'><b><a href='/kidney_disease_svm_std.pkl'>kidney_disease_svm_std.pkl</a></b></td>
				<td style='padding: 8px;'>Serialized SVM model with standard scaling</td>
			</tr>
			<tr style='border-bottom: 1px solid #eee;'>
				<td style='padding: 8px;'><b><a href='/README.md'>README.md</a></b></td>
				<td style='padding: 8px;'>Project README file</td>
			</tr>
			<tr style='border-bottom: 1px solid #eee;'>
				<td style='padding: 8px;'><b><a href='/project_tree.txt'>project_tree.txt</a></b></td>
				<td style='padding: 8px;'>Text file of the project structure</td>
			</tr>
			<tr style='border-bottom: 1px solid #eee;'>
				<td style='padding: 8px;'><b><a href='/.ipynb_checkpoints/'>.ipynb_checkpoints/</a></b></td>
				<td style='padding: 8px;'>Jupyter notebook checkpoint folder</td>
			</tr>
			</table>
		</blockquote>
	</details>
</details>


## Getting Started

### Prerequisites

This project requires the following dependencies:

- **Programming Language:** unknown

### Installation

Build  from the source and intsall dependencies:

1. **Clone the repository:**

    ```sh
    ❯ git clone ../
    ```

2. **Navigate to the project directory:**

    ```sh
    ❯ cd 
    ```

3. **Install the dependencies:**

echo 'INSERT-INSTALL-COMMAND-HERE'

### Usage

Run the project with:

echo 'INSERT-RUN-COMMAND-HERE'

### Testing

 uses the {__test_framework__} test framework. Run the test suite with:

echo 'INSERT-TEST-COMMAND-HERE'

---

## Getting Started

### Prerequisites

This project requires the following dependencies:

- **Programming Language:** Python 3.10+
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn, jupyter

### Installation

Build from the source and install dependencies:

1. **Clone the repository:**

    ```sh
    ❯ git clone <your-repo-url>
    ```

2. **Navigate to the project directory:**

    ```sh
    ❯ cd <your-project-folder>
    ```

3. **Create a conda virtual environment and activate it:**

    ```sh
    ❯ conda create -n kidney-env python=3.10 -y
    ❯ conda activate kidney-env
    ```

4. **Install the required Python libraries:**

    ```sh
    ❯ pip install pandas numpy scikit-learn matplotlib seaborn jupyter
    ```
    Or, if `requirements.txt` is provided:
    ```sh
    ❯ pip install -r requirements.txt
    ```

### Usage

Run the project:

1. **Start Jupyter Notebook:**

    ```sh
    ❯ jupyter notebook
    ```

2. **Open the data cleaning notebook for preprocessing:**

    ```sh
    ❯ kidney_disease_data_cleaning.ipynb
    ```

3. **Load and use pre-trained models in Python:**

    ```python
    import joblib
    import pandas as pd

    # Load a pre-trained logistic regression model
    model = joblib.load("kidney_disease_logistic_mm.pkl")

    # Load cleaned data
    data = pd.read_csv("kidney_disease_cleaned_data.csv")

    # Make predictions
    predictions = model.predict(data)
    print(predictions)
    ```

### Testing

There is no formal test framework used in this project. You can manually test the models by running the prediction code above and verifying outputs on sample data.
---

## Roadmap

- [X] **`Data Collection`**: Gather kidney disease datasets (Excel & CSV).  
- [X] **`Data Cleaning & Preprocessing`**: Clean missing values, handle categorical features, and preprocess the data.  
- [X] **`Model Training`**: Train Logistic Regression and SVM models with scaling (Min-Max and Standard Scaler).  
- [X] **`Model Serialization`**: Save trained models as `.pkl` files for future predictions.  
- [X] **`Prediction Script / Notebook`**: Implement a script or notebook to load models and make predictions on new data.  
- [X] **`Evaluation & Reporting`**: Generate model evaluation metrics and visualizations.  
- [X] **`README Enhancement`**: Add detailed instructions, project index, and dataset summary.  
---

## Contributing
This project is based on Kaggle datasets. Direct contributions are not required, but you can still contribute in the following ways:
- **💬 Share Insights**: If you try the project or improve preprocessing/modeling, feel free to share your findings in forums or comments on Kaggle.  
- **🐛 Report Issues**: If you find errors in the notebooks or models, you can log issues in your own fork or via Kaggle discussion threads.  
- **💡 Improve Locally**: You can create your own version of the notebooks or models and experiment with different approaches.  

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your LOCAL account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone .
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to LOCAL**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>
---

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com/anand2797/Practice-data-cleaning.git/graphs/contributors">
      <img src="https://contrib.rocks/image?repo=<username>/<repo>">
   </a>
   *(This will display once the project is hosted on GitHub)*
</p>
</details>

---

## License

 is protected under the [GNU General Public License v2.0](./LICENSE) License. For more details, refer to the LICENSE file in this repository.
---


## Acknowledgments

- Thanks to the **Kaggle community** for providing the kidney disease dataset.  
- Inspiration and reference materials were taken from standard machine learning resources and tutorials.  
- Any libraries or tools used (pandas, scikit-learn, matplotlib, seaborn, Jupyter) are acknowledged.  

<div align="right">
[Back to Top](#top)
</div>


---
