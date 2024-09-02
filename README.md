# ResumeRefine AI
ResumeRefine AI is a state-of-the-art tool that enhances your resume to align perfectly with job descriptions. It analyzes and refines your resume content, ensuring it matches the key requirements of your target job. This application streamlines the process of resume customization, giving you a competitive edge in your job search.

## Features

- **Automated Resume Tailoring**: Aligns your resume sections with specific job descriptions.
- **ATS Optimization**: Ensures the tailored resume section is optimized for Applicant Tracking Systems (ATS).
- **Keyword Matching**: Prioritizes the use of relevant keywords from the job description.
- **User-Friendly Interface**: Built on Gradio for a seamless user experience.

## Technology Stack

- **[Ollama](https://ollama.com/)**: Used for running local LLMs, particularly the "llama3.1:8b-instruct-q3_K_S" model.
- **[Langchain](https://langchain.com/)**: Creates chains for integrating different components of the ResumeRefine AI.
- **[Gradio](https://gradio.app/)**: Provides the user interface, enabling easy interaction with the ResumeRefine AI.

## Prerequisites

- Python 3.8 or later
- Ollama installed and running on `localhost` at port `11434` with the "llama3.1:8b-instruct-q3_K_S" model downloaded.
- Required Python libraries:
  - `psutil`
  - `gradio`
  - `langchain-experimental`

Install the dependencies using:

```bash
pip install langchain-experimental psutil gradio
```

## Usage

1. **Run Ollama**: Ensure Ollama is running locally with the "llama3.1:8b-instruct-q3_K_S" model.
2. **Launch the ResumeRefine AI**: Run the jupyter notebook to start the Gradio interface.
3. **Interact**: Use the Gradio interface to upload targeted job description, name of resume section to be refined and its content. Press submit for generating tailored resume section.

## UI

![ResumeRefineAI](https://github.com/abhijitchavda/ResumeRefineAI/blob/main/UI.jpg?raw=true)

## Contributing

Contributions are welcome! If you’d like to improve this project, feel free to fork this repository, make your changes, and submit a pull request.



