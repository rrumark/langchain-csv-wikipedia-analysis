# langchain-csv-wikipedia-analysis
![image](https://github.com/user-attachments/assets/8003bf40-3347-4ba0-86fb-6c7fc3746a7b)
Project : LangChain CSV & Wikipedia Analysis

Notebook: langchain_csv.ipynb

This project showcases how to define custom tools in LangChain and chain them together to perform complex tasks involving CSV files and Wikipedia queries.

Key Components

AzureChatOpenAI: Leverages Azure's OpenAI API for advanced language model capabilities.

Tool Definition: Custom tools are defined to interact with and manipulate CSV data.

Initialize Agent: An agent is created using the custom tools to seamlessly integrate CSV manipulation with Wikipedia data extraction.

Example Output

Question: Pick a random place from the Netherlands. Find information about that place. Then, take a fun fact from that information and write a column about it.

Agent Execution:

Entering new AgentExecutor chain...

Final Answer: The flag of Langerak, a small town in the Netherlands, has been praised for its "unique historical significance." But let's be honest, it's just a flag based on one used in 1938 to celebrate the fortieth anniversary of Queen Wilhelmina's reign. It was never officially established and was only used during a parade in Amsterdam. Let's not forget that it also contains the city's coat of arms. So let's stop pretending this is some huge historical symbol. It's just a flag with a questionable connection to a royal event.

Finished chain.

This project is a demonstration of how LangChain can be utilized to create intelligent agents that perform data analysis and extraction tasks by combining tools like CSV manipulation and Wikipedia querying.

