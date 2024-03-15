# Empower Your Learning: Personalized Roadmap Tool

Welcome to the Empower Your Learning repository! This project aims to revolutionize the way you approach your learning journey by providing a personalized roadmap tailored to your field of study. Say goodbye to confusion and hello to clarity with our AI-powered tool.

## Features

- **Personalized Learning Paths:** Input your field of study, and our tool generates a customized roadmap, guiding you through the essential courses and prerequisites.
  
- **AI-Powered Recommendations:** Leveraging state-of-the-art AI technology, our tool ensures that your learning journey is efficient and effective.

- **Expert Guidance:** Benefit from the expertise of industry professionals. The prerequisite structures are curated by experienced practitioners, ensuring you're on the right track.

- **User-Friendly Interface:** Built with Streamlit, our tool offers a seamless user experience, making it easy for anyone to navigate and utilize.

- **Content and Article Creation:** Ideal for content and article creators, our tool provides structured course roadmaps that can be seamlessly integrated into educational content.

- **No Paid API Usage:** Empower Your Learning utilizes free APIs from Gemini Pro and Graphviz, ensuring accessibility without the need for costly subscriptions.

## Getting Started

To get started with Empower Your Learning, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/jhasid/customiseLearningPath.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Configure the environment variables:
   - Obtain an API key for the Generative AI API from [Google](https://cloud.google.com/)
   - Set up your environment variables in a `.env` file:
     ```dotenv
     GOOGLE_API_KEY=your_api_key_here
     ```

4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

5. Enter your field of study and generate your personalized course roadmap!

6. conda install graphviz  #in case of (.)dot issue found


## Contributing

We welcome contributions from the community! Whether it's bug fixes, feature enhancements, or feedback, your input is valuable to us. Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

