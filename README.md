# Application Tracking System using Gemini Pro

By [<b>Mohammad Nayeem</b>](https://www.linkedin.com/in/mohammad-nayeem-1156a31b9/)

Connect with me on social media and explore my work:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/mohammad-nayeem-1156a31b9/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github)](https://github.com/Nayeem114477)

## About The Project

![](https://github.com/Nayeem114477/Application_Tracking_System/blob/main/Artifacts/screen.png)
<br>
![](https://github.com/Nayeem114477/Application_Tracking_System/blob/main/Artifacts/result.png)

The Smart Applicant Tracking System (ATS) is a cutting-edge tool designed to enhance the resume evaluation process. Leveraging advanced Generative AI models from Google, the system empowers users to submit their resumes for a comprehensive analysis based on a provided job description. The system, equipped with a keen understanding of the tech industry, including software engineering, data science, and big data engineering, evaluates resumes in the highly competitive job market. Users can upload their resumes in PDF format, and the system extracts relevant information using PyPDF2. The generated response includes a percentage match with the job description, a list of missing keywords, and a refined profile summary. This innovative solution aims to assist individuals in improving their resumes for optimal performance in the competitive job landscape. The Streamlit web application provides a user-friendly interface, making the resume enhancement process efficient and accessible.

## Built With

- Streamlit  
- PyPDF2  
- Google Generativeai  
- Python-dotenv  

## Getting Started

This will help you understand how to set up the project locally.

### Installation Steps

#### Option 1: Installation from GitHub

1. **Clone the Repository**

```bash
git clone https://github.com/Nayeem114477/Application_Tracking_System.git
cd Application_Tracking_System
```

2. **Create a Virtual Environment** (Optional but recommended)

```bash
conda create -p env_name python==3.10 -y
```

3. **Activate the Virtual Environment**

```bash
conda activate env_name/
```

4. **Install Dependencies**

```bash
pip install -r requirements.txt
```

5. **Run the Project**

```bash
streamlit run app.py
```

6. **Access the Application**

Open the browser to the localhost URL shown in your terminal.

## API Key Setup

To use this project, you need an API key from Google Gemini:

1. **Get Your API Key:**  
   [Generate your key here](https://makersuite.google.com/app/apikey)

2. **Configure Your Key:**  
   Create a `.env` file in the project root directory with the following content:
```env
GOOGLE_API_KEY=your_api_key_here
```

> ⚠️ Keep your API key secret. Do not share it publicly.

## Contributing

Contributions are welcome! Feel free to fork this repo and open a pull request.

- Report bugs or request features via GitHub issues.
- Improve the code by creating a new feature branch and opening a PR.

## License

Licensed under the [GNU General Public License v3.0](LICENSE.txt)
---
