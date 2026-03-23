# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

Below is a **sample GitHub report** you can submit for your assignment. It is written as if **you developed a prompt-based schedule management system using an LLM**. You can copy this directly into a **README.md or report document**.

---

# Prompt-Based Schedule Management System

### Leveraging Large Language Models for Intelligent Task Planning

## 1. Problem Statement

Many people struggle to organize their daily schedules efficiently. Traditional calendar or task management tools require manual input and planning, which can be time-consuming and inefficient.

Users often face difficulties such as:

* Forgetting tasks or deadlines
* Poor prioritization of work
* Difficulty adjusting schedules dynamically
* Lack of intelligent assistance for planning

Therefore, there is a need for a **smart scheduling assistant that understands user prompts and automatically organizes tasks**.

---

# 2. Aim

We developed a **Prompt-Based Schedule Management System** powered by a **Large Language Model (LLM)**.

Instead of manually organizing tasks, users can type natural language prompts such as:

> "Schedule my study time for 2 hours after lunch and remind me to finish my assignment before 8PM."

The system then:

1. Understands the prompt using an LLM
2. Extracts task information
3. Automatically schedules tasks
4. Displays them in a calendar dashboard
5. Sends reminders if needed

This allows users to **plan their day simply by describing their schedule in natural language**.

---

# 3. System Architecture

The system consists of the following components:

**User Interface**

* Login page
* Dashboard
* Task creation interface
* Calendar view

**Backend**

* Prompt processing module
* Task extraction system
* Schedule management engine

**LLM Integration**

* Interprets natural language prompts
* Converts prompts into structured tasks

**Database**

* Stores users
* Stores tasks
* Stores schedules

---

# 4. Technology Stack

| Component       | Technology Used        |
| --------------- | ---------------------- |
| Frontend        | Streamlit / HTML / CSS |
| Backend         | Python                 |
| Database        | SQLite                 |
| LLM             | OpenAI GPT API         |
| Version Control | GitHub                 |

---

# 5. System Workflow

1. User logs into the system.
2. User enters a prompt describing their schedule.
3. The LLM interprets the prompt.
4. Task details (time, date, priority) are extracted.
5. The task is added to the schedule.
6. The dashboard updates the calendar view.

---

# 6. System Interface

## Login Page

![Image](https://cdn.dribbble.com/userupload/27689281/file/original-1fbf433a186ba10cd87be9f883be14a8.jpg?resize=400x0)

![Image](https://cdn.dribbble.com/userupload/43018807/file/original-c0218872b7809770177c64624b827e5c.png?format=webp\&resize=400x300\&vertical=center)

![Image](https://cdn.dribbble.com/userupload/45392052/file/8a70f0546bf35742dc78777dd8c1d283.jpeg?resize=752x\&vertical=center)

![Image](https://cdn.dribbble.com/userupload/31271894/file/still-27e2b318ba2e72b9ad5c5ba04454d53e.png?format=webp\&resize=400x300\&vertical=center)

The login page allows users to securely access their schedule manager.

Features include:

* Email and password authentication
* Secure login verification
* Simple and minimal UI for ease of access

After authentication, users are redirected to the dashboard.

---

## Dashboard (Main Page)

![Image](https://s3-alpha.figma.com/hub/file/2233274726417552716/ebdd63a8-181d-4c32-addf-1f3dbc40b6a3-cover.png)

![Image](https://cdn.dribbble.com/userupload/44868652/file/6552e38a2c46559f1865a1b488ce704e.png?resize=752x\&vertical=center)

![Image](https://cdn.dribbble.com/userupload/19755217/file/original-536449e790fcdf52ff2a758f77d53626.png?format=webp\&resize=400x300\&vertical=center)

![Image](https://cdn.dribbble.com/userupload/15086028/file/original-85d55cbb9cb13e565ee9d5d64ad717c4.png?format=webp\&resize=400x300\&vertical=center)

The dashboard is the **central hub of the application**.

Users can:

* View today's tasks
* See upcoming events
* Manage priorities
* Quickly add new tasks

Key components include:

* Task list panel
* Calendar preview
* Prompt input box
* Notifications section

---

## Prompt-Based Task Creation

![Image](https://cdn.jim-nielsen.com/blog/2022/language-inputs-time-examples.png)

![Image](https://images.ctfassets.net/lzny33ho1g45/2tzPssOdQ43yyX2QrCAVzx/67b394ed1903d47f2a7923d5ad37bef2/image3.png)


This is the **core feature of the system**.

Users simply type a prompt like:

> "Schedule gym at 6PM tomorrow and remind me to submit my project before 10PM."

The LLM processes the text and extracts:

* Task name
* Time
* Date
* Priority

The task is then automatically added to the schedule.

---

## Calendar Schedule View

![Image](https://cdn.dribbble.com/userupload/6108986/file/original-74c50457ce515e9b5296e23fa2fcc75b.png?format=webp\&resize=400x300\&vertical=center)

![Image](https://cdn.dribbble.com/userupload/46352521/file/271556dcaf3c489268b8ebb52c90f1e4.png?format=webp\&resize=400x300\&vertical=center)

![Image](https://framerusercontent.com/images/7429s5FbJBgAKTVQneXRYSerkms.webp?height=823\&width=1300)

![Image](https://cdn.dribbble.com/userupload/44607556/file/a70e0b45a89aeba772777730a7adcfdf.png?crop=118x88-3083x2312\&format=webp\&resize=400x300\&vertical=center)

The calendar view helps users visualize their schedule.

Features include:

* Daily view
* Weekly view
* Task reminders
* Drag-and-drop task adjustment

This allows users to **modify schedules easily when priorities change**.

---

# 7. Example Prompt Processing

Example user prompt:

> "Plan my day tomorrow. Study from 9AM to 11AM, attend meeting at 2PM, and workout at 6PM."

The LLM extracts structured tasks:

| Task    | Time       |
| ------- | ---------- |
| Study   | 9AM – 11AM |
| Meeting | 2PM        |
| Workout | 6PM        |

These tasks are automatically added to the calendar.

---

# 8. Advantages of the System

* Reduces manual planning effort
* Uses natural language interaction
* Improves productivity
* Provides intelligent task organization
* Easy to use for beginners

---

# 9. Future Improvements

Possible improvements include:

* Mobile application support
* Smart reminders using notifications
* AI-based priority suggestions
* Integration with Google Calendar
* Voice command scheduling

---

# 10. Conclusion

The Prompt-Based Schedule Management System demonstrates how **Large Language Models can enhance productivity tools**. By allowing users to describe their schedules using natural language prompts, the system simplifies task planning and improves daily organization.

This project highlights the practical applications of **LLMs in real-world problem-solving and productivity management**.

---
