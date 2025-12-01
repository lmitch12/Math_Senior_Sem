# Math_Senior_Sem

## Predicting Celiac Disease Diagnosis Using Different Machine Learning Models

   Celiac disease is an autoimmune disease that can cause serious organ damage. For someone with celiac disease, the ingestion of gluten leads to damage in the small intestine and causes nutrient malabsorption.  Common symptoms include stomach irritation, bloating, gas, diarrhea, and other signs of malnutrition, such as unexplained weight loss and extreme fatigue. Celiac disease is hereditary and develops at some point (usually in childhood) after eating gluten. Left untreated, celiac disease can lead to many long-term health conditions, including osteoporosis and small intestine cancer or non-Hodgkin lymphoma.

   The process to get diagnosed with celiac disease can be lengthy, expensive, and painful. It starts with a blood test measuring tTG-IgA antibody levels. Higher levels indicate celiac disease. This test is only accurate if the patient has been eating gluten. Then, the disease is confirmed with an endoscopic biopsy of the small intestine. Like the blood test, this is only accurate if the patient has been eating gluten. Multiple tissue samples are taken from the duodenum (the entryway to the small intestine) and biopsied.  This procedure is much more invasive than something like a blood test, as well as more expensive. It is not the easiest procedure to undergo. It is not recommended for everyone, especially not children. 

   The goal of this project is to determine if machine learning models can predict celiac disease diagnosis using lab results and patient symptoms, reducing the need for an invasive endoscopy and creating a much simpler, streamlined diagnosis process.

### Key Findings
- RandomForest achieved the best results, with a 91% test accuracy and a 99% recall for patients with celiac disease
- It only misclassified one patient with celiac disease
- Validated on an independent set with a 94% accuracy and 100% celiac recall

# To run this project:
### Clone the repository:
git clone https://github.com/yourusername/celiac-disease-prediction.git
cd celiac-disease-prediction

### Install required packages
pip install -r requirements.txt
