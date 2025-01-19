# **SoulBuddy by AstraVision**

SoulBuddy is an AI-powered spiritual guide that blends ancient wisdom with cutting-edge technology. Designed to provide personalized astrology and numerology insights, SoulBuddy empowers users with actionable recommendations, spiritual guidance, and interactive tools—all tailored to their unique needs.

---

## **Key Features**
1. **Kundali & Horoscope Generation**:
   - Generate detailed birth charts covering all 12 houses of astrology.
   - Provides insights on career, relationships, personal growth, and more.
   - Daily and monthly horoscope predictions.

2. **AI-Powered Recommendations**:
   - Personalized gemstone suggestions based on planetary alignments.
   - Ritual (Pooja) recommendations with explanations of benefits.
   - Meditation, workout, and sleep suggestions aligned with horoscope insights.

3. **Interactive AI Chatbot**:
   - Provides natural language responses to spiritual and astrological queries.
   - Simplifies complex astrology concepts into actionable advice.

4. **Visual Insights Dashboard**:
   - Visualizes trends with graphs, word clouds, and sentiment analysis.
   - Provides direct links to reference materials for validation and inspiration.

---

## **Technologies Used**
- **Backend**:
  - Python (Flask/FastAPI)
  - AstraDB (Vector Store for embeddings)
- **Frontend**:
  - Streamlit/React for dashboard
- **AI & NLP**:
  - GPT-based models for chatbot and insights
  - NLP libraries: SpaCy, Hugging Face
- **Visualization**:
  - Plotly, Matplotlib, WordCloud
- **Data Processing**:
  - Web scraping: BeautifulSoup, Scrapy
  - Sentiment Analysis: TextBlob, VADER

---

## **How It Works**
1. **Input Details**:
   - Users enter their birth details or queries into the platform.
2. **Data Analysis**:
   - The system scrapes and analyzes data from platforms like Google, YouTube, Reddit, and app reviews.
   - It calculates astrological charts and identifies pain points using NLP and sentiment analysis.
3. **Recommendations**:
   - Generates personalized insights, including gemstone suggestions, rituals, and daily guidance.
4. **Dashboard**:
   - Displays actionable insights in an intuitive dashboard with visualizations and links to relevant data.

---

## **Setup Instructions**
### **Prerequisites**
- Python 3.8+
- Git
- AstraDB account for vector storage
- API keys for embedding models (e.g., OpenAI, Google Generative AI)

### **Clone the Repository**
```bash
git clone https://github.com/alok-ahirrao/SoulBuddy-by-AstraVision.git
cd SoulBuddy-by-AstraVision
```

### **Install Dependencies**
Create a virtual environment and install required packages:
```bash
python3 -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### **Configure API Keys**
Create a `.env` file and add the following:
```env
ASTRA_DB_TOKEN=<Your AstraDB Token>
EMBEDDING_API_KEY=<Your Embedding Model API Key>
OPENAI_API_KEY=<Your GPT API Key>
```

### **Run the Application**
Start the backend server:
```bash
python app.py
```

Start the dashboard:
```bash
streamlit run dashboard.py
```

---

## **Screenshots**
![SoulBuddy Dashboard](https://via.placeholder.com/800x400.png?text=Dashboard+Preview)
> Example of the interactive dashboard with visualized insights.

---

## **Challenges and Solutions**
1. **Vector Dimension Mismatch**:
   - Resolved by aligning AstraDB schema with the embedding model’s output dimensions.
2. **Accurate Astrological Calculations**:
   - Implemented Swiss Ephemeris for planetary positions and verified results.
3. **Simplifying Insights**:
   - Built an intuitive dashboard with visualizations to present complex insights clearly.

---

## **Future Improvements**
- Integration with voice assistants for hands-free interaction.
- Expanding to additional spiritual practices like tarot and vastu.
- Multi-language support for broader accessibility.

---

## **Contributors**
- **Alok Ahirrao**: Project Lead
- **Rohit Nehul**: Backend Developer
- **Ganesh Jadhav**: AI and NLP Specialist

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## **Contact**
For questions, feedback, or contributions:
- Email: alok.ahirrao@example.com
- GitHub: [SoulBuddy by AstraVision](https://github.com/alok-ahirrao/SoulBuddy-by-AstraVision.git)
