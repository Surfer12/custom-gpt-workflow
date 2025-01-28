
	# What is a prompt?

	​

	 Summary

	The article discusses effective prompts for ChatGPT. It provides techniques to craft structured prompts, refine answers iteratively, and relay relevant context. The article also explains prompt engineering and how to give ChatGPT a persona. Additionally, it covers the use of delimiters, step-by-step instructions, and examples to improve ChatGPT's responses.

	 Table of Contents

	1. [Give ChatGPT a persona](safari-reader://help.openai.com/en/articles/10032626-prompt-engineering-best-practices-for-chatgpt#:~:text=Give%20ChatGPT%20a%20persona,-Assigning%20a%20persona%20allows%20ChatGPT%20to%20answer%20from%20a%20particular%20role%20or%20perspective.%20This%20can)
	2. [Add delimiters](safari-reader://help.openai.com/en/articles/10032626-prompt-engineering-best-practices-for-chatgpt#:~:text=Add%20delimiters,-Delimiters%20can%20help%20distinguish%20specific%20segments%20of%20text%20within%20a%20larger%20prompt.%20For%20example%2C)
	3. [Provide step-by-step instructions](safari-reader://help.openai.com/en/articles/10032626-prompt-engineering-best-practices-for-chatgpt#:~:text=Provide%20step-by-step%20instructions,-Step-by-step%20instructions%2C%20also%20known%20as%20chain%20of%20logic%20prompting%20or%20chain-of-thought%20prompting%2C)
	4. [Provide examples](safari-reader://help.openai.com/en/articles/10032626-prompt-engineering-best-practices-for-chatgpt#:~:text=Provide%20examples,-This%20technique%20is%20called%20one%20or%20few-shot%20prompting%20%28depending%20on%20the%20number%20of%20examples%29.%20By)
	5. [Be clear and specific](safari-reader://help.openai.com/en/articles/10032626-prompt-engineering-best-practices-for-chatgpt#:~:text=Be%20clear%20and%20specific,-Ensure%20your%20prompts%20are%20clear%2C%20specific%2C%20and%20provide%20enough%20context%20for%20the%20model%20to%20understand)
	6. [Iterative refinement](safari-reader://help.openai.com/en/articles/10032626-prompt-engineering-best-practices-for-chatgpt#:~:text=Iterative%20refinement,-Prompt%20engineering%20often%20requires%20an%20iterative%20approach.%20Start%20with%20an%20initial%20prompt%2C%20review)
	7. [Requesting a different tone](safari-reader://help.openai.com/en/articles/10032626-prompt-engineering-best-practices-for-chatgpt#:~:text=Requesting%20a%20different%20tone,-Use%20descriptive%20adjectives%20to%20indicate%20the%20tone.%20Words%20like%20formal%2C%20informal%2C%20friendly%2C%20professional%2C)
	​


	Learn how to craft effective prompts to get the best out of ChatGPT

	This guide provides essential techniques to help ChatGPT Enterprise users craft effective prompts for high-quality responses. You can fully harness ChatGPT's potential using structured prompts, refining answers iteratively, and relaying relevant context.

	A prompt for a Large Language Model (LLM) is a text input that initiates a conversation or triggers a response from the model. However, it can be in other forms such as an image or audio.

	# What is prompt engineering?

	Prompt engineering is the process of designing and optimizing input prompts to effectively guide a language model's responses.

	# How to craft effective prompts 

	## [[Give ChatGPT a persona]]

	**Assigning a persona allows ChatGPT to answer from a particular role or perspective. This can help produce responses tailored to specific audiences or scenarios.**



	## Add delimiters 

	Delimiters can help distinguish specific segments of text within a larger prompt. For example, they make it explicit for ChatGPT to understand what text needs to be translated, paraphrased, summarized, and so forth.

	Example

	Translate the text delimited by triple quotes to French:

	_Yes we will schedule the meeting next Friday and review your updates to the project plan. Please invite your contacts from the product team and be ready to share next steps._

	## **Provide step-by-step instructions**

	Step-by-step instructions, also known as chain of logic prompting or chain-of-thought prompting, is a technique used with large language models to improve their ability to solve complex problems, especially those requiring multiple steps or reasoning. This approach involves structuring the prompt to encourage the model to generate intermediate steps or reasoning processes that lead to the final answer, rather than attempting to jump directly to the answer.

	You are given text delimited by triple quotes. 

	Step 2 - Provide feedback on grammar and structure 

	Step 3 - Rewrite the text with recommended edits 

	Step 4 - Translate the text to French and to Spanish

	## **Provide examples**

	This technique is called one or few-shot prompting (depending on the number of examples). By providing examples to the model, you can better provide context or illustrate the task at hand. With examples, the model can infer the pattern, style, or type of response expected.

	_Summarize the topic and mood of a piece of text_

	_A molecule, imagine this, is an astonishingly miniscule building block - so diminutive, it’s invisible! Yet, it’s the cornerstone of existence! These specks congregate to conjure, well, everything! Water, air, our very beings!_ 

	_The new OpenAI Custom GPT sharing features released in March are awesome. I look forward to using these to customize who I share my GPT with!_

	# General best practices

	## Be clear and specific 

	Ensure your prompts are clear, specific, and provide enough context for the model to understand what you are asking. Avoid ambiguity and be as precise as possible to get accurate and relevant responses.

	## Iterative refinement 

	Prompt engineering often requires an iterative approach. Start with an initial prompt, review the response, and refine the prompt based on the output. Adjust the wording, add more context, or simplify the request as needed to improve the results.

	## Requesting a different tone

	Use descriptive adjectives to indicate the tone. Words like formal, informal, friendly, professional, humorous, or serious can help guide the model. For instance, "Explain this in a friendly and engaging tone."

	---

	Related Articles

	[

	Best practices for prompt engineering with the OpenAI API

	](https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-the-openai-api)[

	Chat Completions API system message vs Custom Instructions in UI

	](https://help.openai.com/en/articles/8234522-chat-completions-api-system-message-vs-custom-instructions-in-ui)[

	Is ChatGPT biased?

	](https://help.openai.com/en/articles/8313359-is-chatgpt-biased)[

	Data analysis with ChatGPT

	](https://help.openai.com/en/articles/8437071-data-analysis-with-chatgpt)[

	ChatGPT Capabilities Overview

	](https://help.openai.com/en/articles/9260256-chatgpt-capabilities-overview)
