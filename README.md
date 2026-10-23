readme = r'''<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1020,50:172554,100:6D28D9&height=160&section=header&text=Yuti%20Naresh%20Meher&fontSize=36&fontColor=FFFFFF&fontAlignY=38&desc=Software%20Developer%20%7C%20AI%20%26%20Data%20Science&descAlignY=60&descSize=16" width="100%" alt="Yuti Naresh Meher — Software Developer | AI & Data Science" />

### Building intelligent solutions with data, AI, and code.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/er-yuti-m-a26519245/)

</div>

---

## 👋 About Me

I'm **Yuti**, a software developer learning **AI, Machine Learning, and Data Science**. I enjoy solving problems and building practical applications using Python, data analysis, and modern development tools.

- 🌱 Learning Machine Learning, Deep Learning, and Generative AI.
- 🛠️ Building practical projects to strengthen my technical skills.
- 🤝 Open to collaboration, feedback, and learning opportunities.

---

## 🧰 Skills

**Programming:** Python, SQL, JavaScript, HTML, CSS  
**Data Science:** NumPy, Pandas, Statistics, EDA, Data Visualization  
**AI / ML:** Machine Learning, Deep Learning, CNN, NLP, Computer Vision, Generative AI  
**Tools:** Git, GitHub, Flask, FastAPI, React

---

## 🚀 Featured Projects

*Add your real project repositories below. Replace each placeholder link and description before publishing.*

- **Data Science Project** — Data cleaning, exploratory analysis, and visual insights.  
  `Python` · `Pandas` · `NumPy` · [Repository](https://github.com/YOUR_GITHUB_USERNAME/YOUR_DATA_PROJECT)

- **Machine Learning Project** — A predictive model with documented evaluation metrics.  
  `Python` · `Scikit-learn` · [Repository](https://github.com/YOUR_GITHUB_USERNAME/YOUR_ML_PROJECT)

- **Deep Learning / Computer Vision Project** — Image classification or transfer learning with example predictions.  
  `Python` · `CNN` · `TensorFlow / PyTorch` · [Repository](https://github.com/YOUR_GITHUB_USERNAME/YOUR_VISION_PROJECT)

- **Generative AI / RAG Project** — A document question-answering application using retrieval and an LLM.  
  `LLMs` · `Embeddings` · `Vector Search` · [Repository](https://github.com/YOUR_GITHUB_USERNAME/YOUR_RAG_PROJECT)

---

## 📚 Currently Learning

- Data analysis, statistics, and machine learning fundamentals
- Neural networks, CNNs, and model evaluation
- Generative AI, RAG, and AI agents
- Building, documenting, and deploying applications

---

## 🤝 Let's Connect

- **LinkedIn:** [Connect with me](https://www.linkedin.com/in/er-yuti-m-a26519245/)
- **GitHub:** [Explore my repositories](https://github.com/YOUR_GITHUB_USERNAME)

<div align="center">

*Keep learning. Keep building. Keep improving.*

</div>
'''
output_path = "/mnt/data/README_short_clean.md"
with open(output_path, "w", encoding="utf-8") as f:
    f.write(readme)
print(f"Created clean README: {output_path}")
