This is my personal project that I worked from DeepLearning.AI ACP course using OpenAI GPT-4 model as an agent. 

Steps that I follow to make the ACP server works as a senior insurance agent (ACP Client) that connect and communicate with a hospital (ACP server):
1. Building the Senior Insurance Agent with CrewAI; the process includes identify the description, role, and expected output
2. Wrapping the RAG Agent Into an ACP Server; export the codes for agent making inside of the directory called 'my_acp_project' and named it as 'crew_agent_server.py' (it will be used for defining our agent and run the ACP server)
3. Calling an ACP Agent using the Client; after setting up the ACP server as a policy agent in an insurance company, now we can interact with the ACP Agent by sending requests from ACP client
4. Creating the hospital server using Smolagents
5. Connect insurer and hospital agents together by making LLM chains so they can interact then answer some of our questions
6. (Will update soon!)
