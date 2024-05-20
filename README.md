# News Analysis Project: Uncover What Matters

## Overview
This project helps us understand news articles better by performing the following analyses:
1. **Clean Up Articles**: Remove unnecessary clutter like punctuation and common words to focus on the main ideas.
2. **Check the Mood**: Build a system to determine if an article is positive, negative, or neutral about a topic.
3. **Find Connections**: Identify common themes across many articles, such as patterns in tech news.
4. **Aspect Analysis (Optional)**: Gain deeper insights by understanding the sentiment towards different aspects of the news.

## Features
- **Mood Rating**: Determine if the article is positive, negative, or neutral.
- **Short Summary**: Extract key points of the article quickly.
- **Big Ideas**: Identify common themes across many articles.
- **Aspect Analysis**: Understand sentiment towards different aspects of the news.

## Prerequisites
Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Required Python packages: pandas, textblob, openpyxl

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/monalisaburma/news_analysis.git
    ```
2. Navigate to the project directory:
    ```sh
    cd news-analysis-project
    ```
3. Create and activate a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
4. Install the required packages:
    ```sh
    pip install pandas textblob openpyxl
    ```

## Usage
1. Open the Jupyter notebook:
    ```sh
    jupyter notebook
    ```
2. Load the `news_analysis.ipynb` file.
   
3. Follow the steps in the notebook to:
    - Load and clean data.
    - Perform mood analysis.
    - Summarize articles.
    - Identify common themes.
    - Conduct aspect analysis.

## Example
Here's an example of how the data looks after processing:

| Original Article | Cleaned Article | Mood | Summary | Aspect Analysis |
|------------------|------------------|------|---------|------------------|
| Researchers discover a new treatment for cancer. This is a major breakthrough! | researchers discover a new treatment for cancer this is a major breakthrough | Positive | Researchers discover a new treatment for cancer. This is a major breakthrough! | {'Innovation': 'Positive'} |
| City council meeting discusses plans for a new park. The meeting was attended by many residents. | city council meeting discusses plans for a new park the meeting was attended by many residents | Neutral | City council meeting discusses plans for a new park. The meeting was attended by many residents. | {} |

## Contributing
If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
Created by [Monalisa Burma](https://github.com/monalisaburma) - feel free to contact me!

