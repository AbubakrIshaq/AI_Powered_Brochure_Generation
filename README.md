# AI Powered Brochure Generation

This project automates the creation of professional company brochures by leveraging AI to extract and summarize key information from a company's website. It utilizes OpenAI's GPT-4o-mini and GPT-4o models to identify relevant content and generate a structured, client-ready brochure.

## Features

+ __Automated Content Extraction:__ Parses company websites to identify and extract pertinent information such as About Us, Services, and Careers pages.
+ __AI-Driven Summarization:__ Employs llama3.2 to analyze extracted content and to generate coherent and engaging brochure text.
+ __Structured Output:__ Produces brochures in a structured format suitable for clients, investors, and potential recruits.

## Technologies Used

+ __Ollama llama3.2:__ For content analysis and brochure generation.
+ __Python:__ Primary programming language for backend development.
+ __Jupyter Notebook:__ Development environment for prototyping and testing.
+ __JSON:__ Data format for structured communication between components.
+ __Web Scraping/Parsing:__ To extract content from company websites using BeautifulSoup library.
+ __Prompt Engineering:__ Techniques like one-shot prompting for effective AI responses.

## Usage

Provide the company name and primary website URL as inputs. The system will:​

1.Scrape the website to identify relevant pages.
2.Use llama3.2 to extract and summarize content.
3.Generate a structured brochure using GPT-4o.
4.Display the brochure in the notebook interface.









