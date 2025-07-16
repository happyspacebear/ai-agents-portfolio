# AI Workflow Agents Portfolio

A collection of custom AI workflow agents I've developed using n8n and LangChain to automate complex business processes, demonstrate multi-agent orchestration, and showcase practical applications of large language models in enterprise environments.

## Featured Agents

### Multi-Agent Workflow Orchestration
A sophisticated system that coordinates multiple specialized AI agents to produce comprehensive project reports. This agent demonstrates advanced capabilities in autonomous decision-making and task delegation.
- **Technologies**: n8n, LangChain, Claude 3.7 Sonnet, Google Sheets API, Gmail API
- **Key Features**: 
  - Autonomous coordinator agent that orchestrates specialized sub-agents
  - Context-aware memory system for coherent multi-step reasoning
  - Integration with external data sources and tools
  - HTML output formatting for professional communication
- [View implementation details](./multi-agent-workflow/)

### Augmented LLM Workflow
A streamlined workflow that enhances a single LLM with multiple data sources and search capabilities to produce comprehensive automotive project reports.
- **Technologies**: n8n, LangChain, GPT-4.1, Google Sheets API, SerpAPI, Gmail API
- **Key Features**: 
  - Direct integration with external data sources
  - Real-time web search capabilities
  - Structured output formatting
  - Efficient single-agent architecture
- [View implementation details](./augmented-llm-workflow/)

### Single Agent Autonomous Workflow
A fully autonomous agent designed to independently analyze project data, conduct research, and produce comprehensive reports with minimal human intervention.
- **Technologies**: n8n, LangChain, GPT-4.1, Google Sheets API, SerpAPI, Gmail API
- **Key Features**: 
  - Complete autonomous decision-making
  - Self-directed research strategy
  - Quality control and iteration capabilities
  - Professional output formatting
- [View implementation details](./single-agent-workflow/)

## Skills Demonstrated

- **AI Orchestration**: Design of complex multi-agent systems with specialized roles
- **Workflow Automation**: Integration of AI capabilities with business processes and data sources
- **Prompt Engineering**: Creation of robust, context-aware prompts that guide AI behavior
- **System Integration**: Seamless connection of AI models with external APIs and data sources
- **Business Process Optimization**: Automation of complex reporting workflows in enterprise contexts

## Implementation Details

Each agent workflow is built using n8n, a powerful workflow automation platform, combined with LangChain for orchestrating language models. The workflows demonstrate different approaches to solving similar problems:

1. **Multi-Agent Approach**: Divides complex tasks among specialized agents (research, writing, formatting)
2. **Augmented LLM Approach**: Enhances a single LLM with multiple data sources and tools
3. **Autonomous Agent Approach**: Creates a self-directed agent that makes independent decisions

## License

This project is licensed under the MIT License with Attribution - see the [LICENSE](LICENSE) file for details.
