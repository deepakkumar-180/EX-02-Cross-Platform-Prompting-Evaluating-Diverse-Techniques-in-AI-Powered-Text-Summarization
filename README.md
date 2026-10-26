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
<h1>GOOGLE GEMINI -Prompting Techniques in Generative AI</h1>
<h4>Zero-Shot Prompt</h4>
<p>Zero-Shot Prompt Summarize the following article about “The Basics of Blockchain Technology”? At its core, blockchain is a distributed, immutable ledger that facilitates the process of recording transactions and tracking assets in a business network. While it gained mainstream fame as the engine behind Bitcoin, its implications stretch far beyond digital currency. To understand blockchain, one must look at its three defining characteristics: decentralization, transparency, and security through cryptography.How the Architecture WorksThe name "blockchain" is literal. Information is stored in blocks, and each block has a specific storage capacity. When a block is filled, it is closed and linked to the previously filled block, forming a chronological chain.Each block contains three essential elements:The Data: In a financial context, this includes the sender, receiver, and amount.The Hash: Think of this as a digital fingerprint. It is a unique alphanumeric string generated by a mathematical algorithm.The Hash of the Previous Block: This is the "glue" that creates the chain. Because each block references the one before it, any attempt to change a single bit of data in an old block would change its hash, causing a mismatch in all subsequent blocks and alerting the network to a security breach.The Power of DecentralizationIn traditional systems, we rely on centralized authorities—like a bank or a government—to verify transactions. If the bank’s database is hacked or corrupted, the system fails. Blockchain removes this "single point of failure" by using a Peer-to-Peer (P2P) network.Every participant (node) in the network has a copy of the entire ledger. For a new block to be added, the network must reach a consensus. This is often achieved through mechanisms like Proof of Work (PoW) or Proof of Stake (PoS), where nodes validate the data to ensure it is legitimate. This democratic process ensures that no single entity can control or manipulate the history of the data.Transparency vs. PrivacyOne of the most interesting paradoxes of blockchain is its balance of transparency and privacy. While the ledger is public (anyone can see the transaction history), the identities of the users are protected by public-key cryptography. Users are represented by "addresses" (complex strings of characters). This allows for a system where everyone can verify that a transaction occurred without necessarily knowing exactly who was behind it.Beyond CryptocurrencyWhile finance was the first "killer app" for blockchain, the technology is evolving into other sectors:Smart Contracts: These are self-executing contracts with the terms written directly into code, eliminating the need for intermediaries.Supply Chain: Companies can track products from the raw material stage to the shelf, ensuring authenticity and ethical sourcing.Healthcare: Securely sharing patient records between providers while maintaining strict privacy.ConclusionBlockchain is more than just a buzzword; it is a fundamental shift in how we handle trust in the digital age. By moving from "trust in institutions" to "trust in math and code," blockchain provides a framework for a more secure, transparent, and efficient global economy.</p>
<h4>Few-Shot Prompt </h4>
<p> Few-Shot Prompt Example 1 Topic: Artificial Intelligence Summary: Artificial Intelligence is a technology that enables machines to simulate human intelligence, learn from data, and perform tasks such as problem-solving and decision-making.

Example 2 Topic: Cloud Computing Summary: Cloud computing allows users to store and access data and applications over the internet instead of local computers, providing flexibility, scalability, and lower costs.

The Mechanism of Connectivity At its most basic level, IoT is about giving "dumb" objects a digital voice. Whether it is a smart thermostat in a residential home or a pressure sensor in a massive industrial pipeline, these devices collect raw data from their environment. This data is then transmitted via the cloud to a central management system. This connectivity allows for real-time monitoring and remote control, turning isolated hardware into an integrated, interactive ecosystem.

Impact on Efficiency The true value of IoT lies in its ability to automate mundane tasks and provide insights that were previously invisible. In a "Smart City," IoT sensors can monitor traffic flow and adjust signal timing to reduce congestion. In healthcare, wearable devices can monitor a patient's heart rate and automatically alert a doctor if an anomaly is detected. By bridging the gap between the physical and digital worlds, IoT creates a more responsive and efficient environment.

🤖 Machine Learning (ML) Summary: Machine Learning is a subset of Artificial Intelligence that focuses on the development of algorithms that allow computers to learn from and make predictions based on data, improving their accuracy over time without being explicitly programmed.

The Learning Process Traditional programming relies on "if-then" logic provided by a human. In contrast, Machine Learning uses statistical models to find patterns in massive datasets. There are three primary types of learning:

Supervised Learning: The model is trained on labeled data (e.g., teaching an AI to recognize a "cat" by showing it thousands of photos labeled "cat").

Unsupervised Learning: The model looks for hidden patterns or clusters in data without pre-existing labels (e.g., grouping customers by purchasing habits).

Reinforcement Learning: The model learns through trial and error, receiving "rewards" for correct actions (e.g., an AI learning to play a video game).

The Feedback Loop The "Learning" in ML refers to the iterative optimization of the algorithm. As the system processes more data, it refines its internal parameters to reduce the margin of error. This is why your Netflix recommendations or Spotify playlists seem to get "smarter" the more you use the service; the algorithm is constantly updating its understanding of your preferences.

⛓️ How They Converge The most powerful technological shifts happen when these two fields collide. IoT provides the "senses" (the data), while Machine Learning provides the "brain" (the analysis). For example, an IoT-enabled factory might collect vibration data from a machine, and a Machine Learning model can analyze that data to predict exactly when the machine will fail—a concept known as Predictive Maintenance. Together, they transform raw data into actionable intelligence.</p>
<h4> Chain-of-Thought Prompt</h4>
<p>Chain-of-Thought Prompt First identify the main ideas such as the definition of blockchain, how it works, key components (blocks, nodes, and hashing), and its advantages. Then think through these points step by step and organize them logically. Finally, write a clear 500-word summary explaining the basics of blockchain technology?

The Basics of Blockchain Technology
At its most fundamental level, blockchain is a distributed ledger technology (DLT) that allows data to be stored globally on thousands of servers while letting anyone on the network see everyone else's entries in near real-time. This makes it difficult for one user to gain control over the network or to game the system. To understand blockchain, one must move away from the image of a "file" stored on a single computer and instead imagine a shared, digital record book that is constantly synchronized.

The Anatomy of a Block The "chain" is made up of individual blocks of data. Each block contains three things: the data (such as a transaction record), a unique identifier called a hash, and the hash of the previous block in the chain.

The hash is the most critical security component. Generated by complex mathematical algorithms, a hash acts like a digital fingerprint. If even a single character within a block is changed, the hash changes entirely. Because each block contains the hash of the previous one, changing a block would "break" the chain, as all subsequent blocks would now point to an invalid fingerprint. This creates an immutable record; once data is written, it is effectively permanent.

The Power of Nodes and Consensus A blockchain does not live on a central server owned by a bank or a government. Instead, it exists on nodes—individual computers spread across the globe that each hold a full copy of the ledger.

When a new transaction occurs, it is broadcast to these nodes. For the transaction to be added to the chain, the network must reach a consensus. This is a collective agreement among nodes that the transaction is valid. Unlike a traditional bank, where one entity decides which transactions are "real," blockchain uses math-based protocols (like Proof of Work) to ensure that every entry is legitimate. This decentralization ensures that the system remains functional even if several nodes go offline or are attacked.

Why Blockchain Matters The advantages of this architecture are transformative. First, it offers unparalleled transparency; because the ledger is public, any participant can audit the trail of transactions. Second, it provides enhanced security. To hack a blockchain, one would have to alter every block in the chain across more than 50% of the nodes simultaneously—a feat that is computationally and financially nearly impossible.

Finally, blockchain eliminates the "middleman." In traditional systems, we pay fees to banks or clearinghouses to act as the "trusted" third party. Blockchain replaces this human trust with cryptographic proof. This reduces costs, speeds up transaction times, and provides financial access to people who may not have access to traditional banking infrastructure.

In conclusion, blockchain is a foundational technology. While it began with Bitcoin, its ability to create a secure, transparent, and decentralized record of "the truth" makes it a revolutionary tool for everything from voting systems to global supply chains.</p>
## Result


