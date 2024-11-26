

# Customer Segmentation with Flask

This project segments customers based on purchasing behavior and deploys the model using Flask.

#Overview

- Objective: Categorize customers into meaningful segments (e.g., High-Value, Low-Value).  
- Features: Predict customer segments via a simple web interface.

#Directory Structure

```
customer_segmentation/
├── app.py           # Flask backend
├── model.pkl        # Trained model
├── requirements.txt # Dependencies
├── templates/       # HTML files
│   └── index.html
└── static/          # CSS files


#Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-segmentation-flask.git
   cd customer-segmentation-flask
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:
   ```bash
   python app.py
   ```

4. Open in browser:
   ```
   http://127.0.0.1:5000/
   ```

---

#Deployment

For production, you can deploy using Heroku or any cloud platform. Add a `Procfile` with:
```
web: python app.py
```

---

## **Contact**

