# 🏥 Healthcare Diagnostic and Treatment Assistant

## ✅ Features
- Detects possible diseases based on user symptoms.
- Suggests treatment options including medicines and lifestyle changes.
- Categorizes urgency level (Low, Medium, High).
- Records user feedback with timestamp.
- Gives health tips for better self-care (for educational use only).

## 🛠 Technology Used
- **Programming Language**: Python
- **Libraries/Tools**:
  - `datetime` – for handling timestamps.
  - Basic file I/O – for saving feedback logs.
  - Console I/O – for user interaction.

## 🔄 How It Works
1. User enters name and describes symptoms.
2. The program checks symptoms against a dictionary of 7 diseases.
3. Displays a possible diagnosis, treatment advice, urgency level.
4. Collects feedback and stores it in a `feedback.log` file with the date and time.

## 📊 Data Collection
- Symptom-to-disease mapping is manually created using a Python dictionary.
- The database includes 7 diseases (e.g., fever, chest pain, cough).
- Source: General health knowledge from public sources, curated for demo purposes.
- No sensitive or real patient data used.

---

> ⚠️ **Disclaimer**: This is an educational project. It does not provide professional medical advice. Always consult a qualified healthcare provider.
