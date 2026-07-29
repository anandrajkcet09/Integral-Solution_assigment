Part 1 – Token Optimization

The scenario was that the AI agent was using around 100,000 input tokens for every query. That increases both cost and response time.

>First optimization:
I reduced the amount of information sent to the model. Instead of sending all available documents, I would send only the most relevant ones using retrieval or filtering.

>Second optimization:
I also simplified the prompt by removing repeated instructions and unnecessary examples. This keeps the prompt shorter while still giving the model enough guidance.

Example result:
Before optimization, the input was around 100,000 tokens. After these changes, it could be reduced to around 30,000 to 50,000 tokens. There may be a small chance of missing less relevant information, but overall the response quality should remain good.