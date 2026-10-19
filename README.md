# AI-Enhanced Career Guidance System

An AI-powered Flask application offering personalized career guidance, dynamic academic pathways, and course recommendations integrated with a MongoDB backend.

## 🚀 Key Features
*   **Career Roadmap Generator**: Context-aware guidance using generative AI models.
*   **Smart Course Finder**: Curated study tracks, including NPTEL data mapping.
*   **Dynamic Assessment Infrastructure**: Graded question banks (GAQ) across multiple difficulty tiers.
*   **Utility Modules**: Built-in QR generation for roadmap sharing.

## 🛠️ Project Structure
```text
├── app.py                  # Flask application entry point
├── course_finder.py        # Course tracking and recommendation logic
├── qr_generator.py         # QR code generation utility
├── static/                 # CSS, JS, and Images
├── templates/              # HTML frontend components
└── api_request_content.txt # Upstream API configuration specs
```

## 💻 Technical Setup

### Prerequisites
*   Python 3.8+
*   MongoDB Server (`localhost:27017`)

### Installation & Execution
1.  **Clone the repository:**
    ```bash
    git clone https://github.com
    cd AI-Enhanced-Career-Guidance-System
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Configure environment variables** in a `.env` file (`MONGO_URI`, `SECRET_KEY`, `MISTRAL_API_KEY`).
4.  **Setup MongoDB database** named `Community_Savvyai` with collections for `GAQ` and `NPTEL_Course_Details`.
5.  **Run the application:**
    ```bash
    python app.py
    ```
