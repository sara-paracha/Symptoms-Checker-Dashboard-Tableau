## **Symptoms Checker Dashboard - Tableau Implementation**

### **Overview**

This Tableau dashboard provides an interactive symptoms checker that allows users to select their symptoms and receive information about potential diseases, recommended treatments, and precautionary measures. It's designed for healthcare education and preliminary self-assessment purposes.

### **Features**

- Interactive Symptom Selection: Filter and select from a comprehensive list of symptoms
- Condition Probability Analysis: Visual representation of likely conditions based on selected symptoms
- Treatment Information: Details on medications and therapies for identified conditions
- Precaution Guidelines: Preventive measures
- Data Export: Ability to export results for personal reference

### **Dashboard Components**

### 1\. Symptom Selector Panel

- Searchable list of symptoms with category filters
- Multi-select capability with selected symptoms counter

### 2\. Results Dashboard

- Condition probability chart (bar/radar visualization)
- Top 3 likely conditions with confidence percentages
- Detailed information for each condition
- Treatment options with dosage information
- Precautionary measures categorized by type

### 3\. Interactive Elements

- Tooltips with additional information on hover
- Filter actions between dashboard components
- Export to PDF/CSV functionality

### **Implementation Steps**

### 1\. Data Preparation

- Clean and structure symptom/disease data in Excel or CSV format
- Establish relationships between tables
- Calculate probability scores for symptom-disease correlations

### 2\. Tableau Workbook Setup

- Connect Tableau to your data source (Excel, CSV, or database)
- Create relationships between tables using appropriate keys
- Build necessary calculated fields for probability calculations

### 3\. Dashboard Design

- Create symptom selection interface using filter actions
- Design condition probability visualization
- Implement treatment and precaution information cards
- Add interactive elements and tooltips

### 4\. Testing and Validation

- Test all filter interactions
- Validate probability calculations
- Ensure mobile responsiveness
- Verify export functionality

### **Example Scenarios**

- **User selects:** Runny nose, cough, sore throat → **Output:** Possible common cold → **Advice:** Rest, hydration, acetaminophen for fever, avoid antibiotics unless prescribed.
- **User selects:** Fever, abdominal pain, diarrhea → **Output:** Possible food poisoning → **Advice:** Hydrate with electrolytes, rest, seek doctor if blood in stool or persistent high fever.
- **User selects:** Chest pain, shortness of breath → **Output:** Red Flag → **Advice:** Call emergency services immediately.

### **Future Enhancements**

- Symptom search bar for faster selection
- Integration with a medical API for expanded condition coverage
- Multi-language support

### **Educational Purpose Only**

This tool is designed for health awareness and educational purposes. It should never replace medical judgment, physical examination, or lab tests. Always follow your doctor’s advice.
