# StudyForum

StudyForum is a Django-based web application for creating and joining discussion rooms, messaging with others, and sharing knowledge.

## Features

- Secure user authentication (register, login, logout)
- Create, update, and delete of rooms and messages ( with user based restrictions on rooms/messages they may post, update or delete)
- Gives users ability to Host or join multiple rooms
- Browse topics and posts efficiently using search tab or feed activity
- View spefic user profiles for their recent activity/ posts
- Responsive UI for desktop and mobile
- User profile customization with image uploading for profile pictues

## Project Images

![StudyForum-SampleVid](https://github.com/user-attachments/assets/338f89c9-7158-402e-8f72-97c8779c73e4)

#### Home Page
<img width="2762" height="1591" alt="image" src="https://github.com/user-attachments/assets/5e11eadd-e6a3-4e46-9edf-f51e2ca5a675" />

#### Example Room
<img width="1436" height="952" alt="image" src="https://github.com/user-attachments/assets/cbb595f4-e8d5-4aab-bde1-6bd82ec29f29" />


### Prerequisites

- Python 3.8+
- pip

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/studybud.git
   cd studybud
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   venv\Scripts\activate  # On Windows
   # source venv/bin/activate  # On Mac/Linux
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

6. **Open your browser and visit:**
   ```
   http://127.0.0.1:8000/
   # or given server link after server running
   ```

## License

MIT License.

---
