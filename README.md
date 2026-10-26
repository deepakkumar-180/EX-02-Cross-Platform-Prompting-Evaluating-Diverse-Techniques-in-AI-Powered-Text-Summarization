# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed
## Algorithm
## OUTPUT
<h1>CHAT GPT - Prompting Techniques in Generative AI</h1>
<b>Prompting techniques are methods used to give instructions to Generative AI models such as ChatGPT. They help the AI understand the user's requirements and generate accurate, relevant, and useful responses. Four common prompting techniques are zero-shot, few-shot, chain-of-thought, and role-based prompting.</b>
<h4>1. Zero-Shot Prompting</h4>
<p>Definition: Zero-shot prompting is a technique in which the user asks the AI to perform a task without providing any examples.

The AI uses the knowledge it learned during training to understand the instruction and generate an answer.

Example prompt:

“Explain the basics of blockchain technology in simple English.”

Output:

Blockchain is a digital system that stores information in blocks linked together securely. It is used in cryptocurrencies, banking, healthcare, and supply chain management.
Advantages:
- Simple and easy to use.
- Saves time because no examples are required.
- Suitable for general questions and simple tasks.
- </p>
<h4>2. Few-Shot Prompting</h4>
<p>Definition: Few-shot prompting is a technique in which the user provides a few examples to the AI before asking it to perform a similar task.

These examples help the AI understand the expected format, pattern, or style of the answer.

Example prompt:

Classify the following technologies:
- Bitcoin — Cryptocurrency
- Ethereum — Blockchain platform
- Litecoin — ?
Output:

Litecoin — Cryptocurrency.

In this example, the AI learns the expected classification pattern from the given examples and applies it to the new input.

Advantages:
- Improves consistency in responses.
- Helps the AI follow a specific format.
- Useful when a task requires examples to clarify the expected answer.
Applications: Sentiment analysis, text classification, data extraction, and formatted content generation.</p>
<h4>3. Chain-of-Thought Prompting</h4>
<p>Definition: Chain-of-thought prompting encourages an AI model to work through intermediate reasoning steps when solving a complex problem.

It is particularly useful for mathematical calculations, logical problems, and multi-step tasks. A user can ask the AI to explain the method used to reach an answer.

Example prompt:

“A student has 5 blocks of data, and each block contains 10 transactions. Calculate the total number of transactions. Explain the steps.”

Output:

Step 1: Number of blocks = 5.

Step 2: Transactions in each block = 10.

Step 3: Total transactions = 5 × 10 = 50.

Therefore, the total number of transactions is 50.

Advantages:
- Helps organize complex problems into smaller steps.
- Makes solutions easier to understand and check.
- Supports mathematical and logical problem-solving.
Applications: Mathematical problem-solving, logical reasoning, planning, and multi-step question answering.

Note: A step-by-step explanation can help users understand a solution, but it does not guarantee that the answer is correct.</p>
<h4>4. Role-Based Prompting</h4>
<p>Definition: Role-based prompting is a technique in which the user assigns a specific role or identity to the AI to guide its response.

The assigned role helps determine the tone, language, level of detail, and perspective of the answer.

Example prompt:

“You are an experienced computer science teacher. Explain blockchain technology to undergraduate students using simple English and real-world examples.”

Output:

Blockchain is a digital ledger that records transactions securely. Information is stored in blocks, and each block is connected to the previous one. For example, blockchain can help track products from manufacturers to customers.

Advantages:
- Produces answers suited to a particular audience.
- Helps maintain a suitable tone and writing style.
- Makes explanations more relevant to specific tasks.
Applications: Education, technical writing, programming assistance, customer support, and professional content creation.</p>

## Result


