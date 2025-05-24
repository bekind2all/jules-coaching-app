# 레몬 코치 - 상큼 단단한 하루 만들기 앱

## Introduction

"레몬 코치" (Lemon Coach) is a web application designed for daily self-reflection and motivation. It helps users build positive habits, set daily intentions, and offers a simple way to connect with a life coach for personalized guidance.

(Korean: "레몬 코치"는 일상적인 자기 성찰과 동기 부여를 위해 설계된 웹 애플리케이션입니다. 사용자가 긍정적인 습관을 형성하고, 매일의 다짐을 설정하며, 개인 맞춤 지도를 위해 라이프 코치와 쉽게 연결될 수 있도록 돕습니다.)

## 주요 기능 (Key Features)

*   **Dynamic Daily Content:** Displays the current date ("오늘은 YYYY년 MM월 DD일입니다") and a unique positive affirmation each day to inspire users.
*   **Daily Check-in (일일 체크인):** Allows users to reflect on their well-being and preparedness for the day by answering five questions with checkboxes:
    *   오늘 기분은 어떠신가요? (How are you feeling today?)
    *   어제 할 일을 다 하셨나요? (Did you complete your tasks yesterday?)
    *   자기 관리를 위한 시간을 가지셨나요? (Did you take time for self-care?)
    *   동기 부여가 되시나요? (Are you feeling motivated?)
    *   오늘 무엇에 감사하시나요? (What are you grateful for today?)
*   **Today's Goal (오늘의 목표):** An input field for users to set a single, actionable goal for the day.
    *   Placeholder: "오늘 하고 싶은 일 한 가지는 무엇인가요?" (What is one thing you want to do today?)
*   **Word of Encouragement (격려의 말):** A textarea for users to write a supportive message to themselves.
    *   Placeholder: "자신에게 격려의 메시지를 작성하세요" (Write a message of encouragement to yourself.)
*   **Data Persistence (데이터 지속성):** "Today's Goal" and "Word of Encouragement" entries are automatically saved in the browser's local storage. This data is retained for the current day and cleared if the date changes, allowing for fresh daily entries.
*   **Personal Coaching Form (개인 코칭 신청):** A simple form (Name, Phone, Email, Request) that, upon submission, prepares a `mailto:` link to request coaching services from `hyjune0314@gmail.com`.
    *   The email subject is pre-filled with "New Coaching Application from [User's Name]".
*   **Responsive Design (반응형 디자인):** The application's layout is optimized for a seamless experience on both desktop and mobile devices, ensuring all features are accessible and easy to use on any screen size.

## 사용 방법 (How to Use)

### Locally
1.  Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/jules-coaching-app.git
    ```
    (Replace `your-username` with the actual GitHub username if different)
2.  Navigate to the project directory:
    ```bash
    cd jules-coaching-app
    ```
3.  Open the `index.html` file in your preferred web browser.

### Online (GitHub Pages)
The application will be accessible online via GitHub Pages once deployed.
*   **URL:** [GitHub Pages URL will be added here after deployment]

## 사용 기술 (Technologies Used)

*   **HTML:** For the basic structure and content of the application.
*   **Tailwind CSS:** For styling the application and ensuring responsive design. Utilizes utility-first classes for rapid UI development.
*   **Vanilla JavaScript:** For all dynamic functionalities, including:
    *   Displaying the current date and random daily affirmations.
    *   Saving and retrieving data from local storage.
    *   Handling the coaching application form submission via `mailto:`.
    *   Implementing responsive adjustments that go beyond CSS capabilities if needed (though primarily handled by Tailwind).
