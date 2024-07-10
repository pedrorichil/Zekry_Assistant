<h1><span style="color: crimson;">Zekry Assistant</span> - Streamlit Assistant <img src="imgs/slogo.png" alt="Streamlit logo" width="50" style="border-radius: 25px;"/></h1>

<p align="center">
  <img src="imgs/streamly_readme.png" alt="Zekry Assistant image" width="300" style="border-radius: 45px;"/>
</p>

Zekry Assistant is an AI Assistant that was designed to supercharge the development experience with the Streamlit framework. It acts as an AI-infused sidekick, offering on-the-fly assistance 🚀, code snippets ✂️, and a deep dive into Streamlit's rich api code. 🧪

## Dynamic Features:

- Interactive Chat Interface 💬: Engage in a lively chat with Zekry Assistant, asking anything from simple how-tos to complex Streamlit queries. The assistant is equipped to understand and respond with pertinent information, making the interaction both enriching and delightful.

- Code Snippet Wizardry 🧙‍♂️: Zekry Assistant conjures up ready-to-use code snippets for common Streamlit scenarios. This magic is especially handy for beginners who are getting to grips with Streamlit and seasoned pros looking to expedite their code-writing spells.

- Update Oracle 📜: Always in the loop, Zekry Assistant taps into the latest happenings of the Streamlit universe. Whether it's a fresh release or a minor tweak, Zekry Assistant is your go-to source for the most recent and relevant Streamlit enlightenment.

- A Personal Touch 🎨: Decked out with custom CSS and the potential for further personalization, Zekry Assistant's UI/UX shines, offering a user experience that's both engaging and aesthetically pleasing.

## Insightful Logic and Capabilities:

At the heart of Zekry Assistant lies a sophisticated AI engine 🤖, trained on a plethora of data, including the vast expanses of Streamlit's documentation, forums, and community contributions. This training enables the assistant to understand context, maintain conversational flow, and provide accurate, context-aware advice.

Zekry Assistant's backend is a creative use of session state management, providing Zekry Assistant with a memory, making for a consistent and coherent conversation for all your coding assistances 🧠.

With Zekry Assistant's caching mechanisms under the hood for performance optimization, and a comprehensive error handling protocol 🛠️, Zekry Assistant ensures a smooth sail through the sometimes choppy waters of coding challenges.

Zekry Assistant embraces the future with open arms, designed to be extensible and modular. The integration of LangChain adds for a fuller and seamless conversational experience, making it not just an assistant but a developer's companion 🤝.

In the vibrant world of Streamlit development, Zekry Assistant shines as a beacon of innovation and practicality. It's not just an AI assistant; it's a testament to the harmonious blend of human creativity and artificial intelligence, all wrapped up in a user-friendly package 🎁. Whether you're a novice coder or a seasoned developer, Zekry Assistant is here to light up your coding journey with a spark of AI brilliance ✨.

## Setup Instructions

To get Zekry Assistant up and running on your local machine, follow these steps:

### Prerequisites

- Python 3.10 or higher
- Pip package manager

### API Keys

Use secrets.toml an add your OpenAI API key or set your enviroment variable OPENAI_API_KEY to your API key.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/pedrorichil/Zekry_Assistant.git
cd Zekry_Assistant
```

2. Create and activate a virtual environment (optional but recommended):
```bash
python3 -m venv venv
source venv/bin/activate # On Windows use venv\Scripts\activate
```

3. Install the required packages:

```bash
pip install -r requirements.txt
```

### Running the Application

To run Zekry Assistant, execute the following command:

```bash
streamlit run main.py
```

This will start the Streamlit server, and you should see output indicating the local URL where the app is being served, typically `http://localhost:80`.

## Using Zekry Assistant

After launching Zekry Assistant, you can interact with it in the following ways:

- **Chat Interface**: Simply type your Streamlit-related queries into the chat interface and hit send. Zekry Assistant will respond with insights, code snippets, or guidance based on your questions.

- **Code Examples**: Ask for code examples by typing queries such as "How do I create a sidebar in Streamlit?" and Zekry Assistant will provide you with the relevant code.

- **Latest Updates**: To get the latest updates from Streamlit, type "What's new with Streamlit?" or similar questions.

Remember to check the sidebar for additional features and settings that you can customize according to your needs.

## Contributions

If you'd like to contribute to Zekry Assistant, please fork the repository and create a pull request with your features or fixes.

## License

Zekry Assistant is released under the [MIT License](LICENSE). See the `LICENSE` file for more details.
