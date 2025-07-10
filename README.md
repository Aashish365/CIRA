````markdown
# Contextual Information Retrieval Assistant (CIRA) Powered by Local Neural Language Model (LNLM)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[cite_start]A capstone project report for the B.Tech degree in Computer Science and Engineering at Lovely Professional University[cite: 36].

[cite_start]![Lovely Professional University Logo](https://i.imgur.com/8w3vG2x.png) [cite: 34]

---

## 📖 About The Project

[cite_start]**Contextual Information Retrieval Assistant (CIRA)** is an AI-powered chatbot designed to be tailored to specific websites[cite: 103]. [cite_start]Traditional chatbots often fall short in resolving user queries, typically redirecting to a human agent or only answering FAQs[cite: 101, 102]. [cite_start]CIRA overcomes these limitations by integrating website content scraping and natural language processing powered by open-source Large Language Models (LLMs)[cite: 104]. [cite_start]This allows for the rapid and cost-effective deployment of intelligent chatbots that provide relevant and informative support[cite: 105].

[cite_start]Our platform is adaptable to various domains, including educational institutions, healthcare providers, and hosting platforms, enhancing the overall user experience[cite: 106]. [cite_start]CIRA enables users to extract answers directly from websites, eliminating time-consuming searches[cite: 107]. [cite_start]For instance, a survey showed that finding specific university fee information could take over 20 minutes for some students, while CIRA provided the same information in seconds[cite: 108]. [cite_start]CIRA leverages domain-specific data and powerful AI to deliver accurate, tailored information while prioritizing user security and privacy[cite: 109, 203].

---

## ✨ Key Features

* [cite_start]**Website Content Scraping:** Automatically scrapes and extracts relevant text, images, and links from a provided website to build its knowledge base[cite: 233, 234].
* [cite_start]**Advanced NLP:** Utilizes open-source Large Language Models (LLMs) like Meta's LLaMA2 to understand user queries and generate contextually relevant responses[cite: 198, 205, 236].
* [cite_start]**High Customization:** Offers a user-friendly dashboard for website owners to customize the chatbot's appearance, including colors, fonts, logos, and initial messages[cite: 240, 278, 316].
* [cite_start]**Easy Integration:** Website owners can add the chatbot to their site by simply pasting a single line of JavaScript code[cite: 255, 312].
* [cite_start]**User Statistics:** Provides a dashboard to view chatbot statistics, such as the total number of views and user engagement by country[cite: 319, 325].
* [cite_start]**Human-in-the-Loop:** Includes an optional feature to have a human review and select the best response from multiple AI-generated options before it's sent to the user[cite: 327].

---

## 🛠️ Built With

* [cite_start]**Backend:** PHP Laravel Framework [cite: 272]
* [cite_start]**Frontend:** HTML, CSS, JavaScript [cite: 272]
* [cite_start]**AI Model:** LLaMA 2 by Meta [cite: 139, 279]
* **Database:** MySQL (inferred from Laravel usage)

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* PHP (latest version recommended)
* Composer
* Node.js & npm
* A web server like Apache or Nginx
* MySQL Database

### Installation

1.  **Clone the repo**
    ```sh
    git clone [https://github.com/your_username/CIRA.git](https://github.com/your_username/CIRA.git)
    ```
2.  **Install PHP dependencies**
    ```sh
    composer install
    ```
3.  **Install JS dependencies**
    ```sh
    npm install
    ```
4.  **Create a copy of your .env file**
    ```sh
    cp .env.example .env
    ```
5.  **Generate an app encryption key**
    ```sh
    php artisan key:generate
    ```
6.  **Configure your `.env` file** with your database credentials and other environment variables.
7.  **Run the database migrations**
    ```sh
    php artisan migrate
    ```
8.  **Start the development server**
    ```sh
    php artisan serve
    ```

---

## ⚙️ How It Works

### For Website Owners: Creating a Chatbot

The process for a website owner to create and deploy their own CIRA chatbot is straightforward:

![Flowchart for creating a CIRA chatbot](https://i.imgur.com/2sZ0w7F.png)
[cite_start]*Figure 1: Flow diagram on how website owners can create their own chatbot system from the CIRA Dashboard[cite: 250].*

1.  [cite_start]**Sign Up:** Create a new account on the CIRA dashboard[cite: 252].
2.  [cite_start]**Create Chatbot:** Enter the chatbot's name, the website URL for data fetching, and a starting message[cite: 253].
3.  [cite_start]**Customize:** Modify the chatbot's name, training data, and UI elements like font, color, and images[cite: 254].
4.  [cite_start]**Embed:** Copy the provided one-line code snippet and add it to your website[cite: 255].
5.  [cite_start]**Deploy:** The chatbot will now be live on your website[cite: 255].

### Behind the Scenes: The Chatbot's Logic

When a user interacts with the chatbot, CIRA performs the following steps to generate a response:

![Flowchart of CIRA's working mechanism](https://i.imgur.com/rN5g4dF.png)
[cite_start]*Figure 2: CIRA's working flow diagram when a user asks a question[cite: 257].*

[cite_start]The data training process involves scraping internal links from the provided website, using AI to determine the most relevant pages based on the user's question, and then feeding the content of those pages to the LLaMA 2 model to generate an accurate answer[cite: 265, 267, 268, 269].

![Flowchart of CIRA's data training process](https://i.imgur.com/H2s5n8c.png)
[cite_start]*Figure 3: CIRA's data training flow diagram[cite: 263].*

---

## 📸 Screenshots

| Dashboard | Chatbot Creation |
| :---: | :---: |
| ![Dashboard Screenshot](https://i.imgur.com/h6Qx77s.png) | ![Chatbot Creation Screenshot](https://i.imgur.com/yD8wQ3t.png) |
| **Chatbot Customization** | **Chatbot in Action** |
| ![Chatbot Customization Screenshot](https://i.imgur.com/s6n7b1f.png) | ![Chatbot in Action Screenshot](https://i.imgur.com/L4Z9gYt.png) |
| **Statistics** | **Answering a Complex Question** |
| ![Statistics Screenshot](https://i.imgur.com/m4h8g2u.png) | ![Answering a complex question](https://i.imgur.com/K3O7V6j.png) |

---

## 📈 Results and Observations

[cite_start]We conducted a survey with students at Lovely Professional University to compare the efficiency of finding specific information using traditional methods versus using CIRA[cite: 216, 381].

### Time Taken to Find Information

* [cite_start]**Without CIRA:** A majority of participants (52%) took over 20 minutes to find the required information[cite: 383].
* [cite_start]**With CIRA:** An overwhelming 76% of participants found the information in under one minute[cite: 383].

![Survey results comparing time taken](https://i.imgur.com/3Yt4p6K.png)

### User Preference

[cite_start]All participants (100%) preferred using CIRA over traditional page hopping[cite: 384].

![User preference survey result](https://i.imgur.com/q4m5Z5m.png)

### Deployment Analysis

[cite_start]CIRA was deployed on the AeonFree hosting service website for 15 days to analyze user engagement[cite: 388, 390]. [cite_start]The results showed that over 85% of users were satisfied with the answers provided, and most queries were successfully resolved across various countries[cite: 393].

| User Satisfaction by Country | Questions Asked and Resolved by Country |
| :---: | :---: |
| ![User Content Level with respect to countries](https://i.imgur.com/c4t3b7f.png) | ![Number of questions asked and if their issue was resolved with respect to the countries](https://i.imgur.com/g9v2m1d.png) |

---

## 📜 Publication and Award

[cite_start]Our research paper on this project was accepted for presentation at the **ICONIC-2024** conference[cite: 395].

![Paper Acceptance Email](https://i.imgur.com/9C3w7nC.png)

[cite_start]Furthermore, our paper was honored as **"The best paper of ICONIC 2024"** among 216 submissions at the conference, which was supported by IBM and IEEE[cite: 397, 398].

![Award Photo](https://i.imgur.com/b9k3f5F.jpg)

---

## 👥 Team

* [cite_start]Ashish Subedi (12018751) [cite: 18, 38]
* [cite_start]Sumit Paudel (120187471) [cite: 19, 40]
* [cite_start]Sameer Khanal (12002504) [cite: 20, 42]
* [cite_start]Gouransh Purohit (12002138) [cite: 21, 44]
* [cite_start]Sanjeev Kumar (12001911) [cite: 22, 46]
* [cite_start]Aashish Bhandari (12000405) [cite: 23, 48]

---

## 👨‍🏫 Mentor

**Mr. [cite_start]Ashim Sharma** [cite: 33, 56]
[cite_start]School of Computer Science and Engineering, [cite: 34, 58]
[cite_start]Lovely Professional University, Phagwara, Punjab[cite: 59, 60].

---

## 🙏 Acknowledgments

We are profoundly thankful to our mentor, **Mr. [cite_start]Ashim Sharma**, for his invaluable guidance and for providing us with this enriching project opportunity[cite: 64]. [cite_start]We have learned a great deal from this experience, which has improved our research abilities and expanded our knowledge[cite: 65]. [cite_start]We also extend our gratitude to our families for their unfailing support throughout this project[cite: 66].

---

## 📄 License

Distributed under the MIT License. See `LICENSE.txt` for more information.
````
