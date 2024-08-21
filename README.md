# Design and Implementation of a Writing Robot: Utilizing Artificial Intelligence in the Creation of Stories and Plays

## Abstract
In recent years, the use of Large Language Models (LLMs) in creative content generation, particularly in the fields of story writing and playwriting, has significantly increased. However, many previous efforts in this area have been limited to simple and shallow uses of these models, often resulting in the creation of superficial texts lacking in complex narrative structure. In this research, we have developed advanced software that, by utilizing large language models and employing them as an intelligent agent, is capable of generating long and complex stories and plays while maintaining narrative coherence and logical progression. Unlike previous models, this software produces deep and meaningful texts by analyzing and contemplating the structure of the story, character development, and the overall storyline. The system takes a multi-step approach to writing, initially forming the overall structure of the story, then determining the characters and their interactions, and finally producing the final text. Additionally, the software features a web-based user interface, allowing users to easily interact with the system and generate their desired stories. Preliminary evidence indicates an improvement in the quality and coherence of the stories and plays produced. This software has significant potential for use in professional projects and could serve as a valuable tool in the creative industries to help writers create complex and high-quality content.

## keywords
Large Language Models; Content Generation; Artificial Intelligence; Story Writing; Playwriting; Intelligent Agents; Web-based User Interface

## How to Run
- **Firstly**, install the dependencies.
- Update the value of the line to include your own API key:
  ```
  os.environ["OPENAI_API_KEY"] = "Your API key here"
  ```
- Modify the model endpoints and name if desired:
  ```
  model = ChatOpenAI(base_url="https://openrouter.ai/api/v1", model="meta-llama/llama-3.1-8b-instruct:free")
  ```
- Run the app by executing:
  ```
  streamlit run story_generator.py
  ```
