
# MedWise

MedWise is an innovative project aimed at diagnosing neural diseases in children using a combination of large language models and specialized machine learning algorithms. The project focuses on providing an initial diagnosis through language processing, allowing users to input symptoms and receive preliminary assessments. It further validates these results using dedicated machine learning models tailored to specific neural disorders, providing binary responses for confirmation.

#Tech Stack 

- Frontend -> Reactjs
- Backend ->Flask
- ML libraries-> Sklearn,Intel's Optimization for XGBoost,Intel's Extension for Scikit-learn,Intel's Distribution of Modin



## Features

- **Initial Diagnosis:**
  - Utilizes large language models for preliminary assessments.
  - Users can input symptoms to initiate the diagnostic process.

- **Specialized Machine Learning Models:**
  - Tailored models for specific neural disorders.
  - Provides binary responses for accurate validation.

- **User-Friendly Interface:**
  - Intuitive design for a seamless user experience.
  - Simplifies the neural disease diagnosis process.

- **Multimedia Resources:**
  - Recommends YouTube videos for detailed treatment plan explanations.
  - Visual and auditory aids enhance user understanding.

- **Comprehensive Content:**
  - Blogs and articles covering various neural diseases.
  - In-depth insights into treatment options and advancements.

- **Accessible Education:**
  - Informative content designed for non-experts.
  - Enhances user understanding of neural disorders.

- **Streamlined Decision-Making:**
  - Supports informed healthcare choices.
  - Integrates technology to improve efficiency.

- **Continuous Learning:**
  - Adapts to new medical knowledge and advancements.
  - Incorporates the latest information for up-to-date results.

- **Transparent Results:**
  - Clear outcomes from both language models and machine learning models.
  - Provides understandable recommendations.

- **Responsive Support:**
  - User assistance throughout the diagnostic process.
  - Addresses user queries and concerns.

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/pr3mkum4r/medwise.git
   ```

2. **Install dependencies:**

   ```bash
   cd medwise
   npm install
   ```

3. **Run the application:**

   ```bash
   npm run dev
   ```
4. **Switch to backend:**
    ```bash
   cd backend
   ```
5. **Install dependencies:**

   ```bash
   pip install requirements.txt
   ```
5. **Run Server:**

   ```bash
   python3 ./app.py
   ```
   
**Backend**

go into api directory using command

```bash
cd api/
```
run server on port 5000 by running command

```bash
 python3 app.py
```

Model was trained on virtual machine by ssh using commands

```bash
 ssh -L 8888:localhost:8888 -J guest@146.152.232.8 ubuntu@100.82.14.144
```

```bash
Running jupyter notebook on localhost:8000
```









