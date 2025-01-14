# Amazon Bedrock multi-agent collaboration Examples

This repository is designed to get you started with Amazon Bedrock multi-agent collaboration by providing a set of examples that demonstrate how it works, and showcasing some of its core capabilities. The field of multi-agent systems is still in its early days, and our goal is to give you some off-the-shelf starter examples that inspire you to tackle your own real world scenarios.

## Getting started

1. To get started navigate to the example you want to deploy in `examples/amazon-bedrock-multi-agent-collaboration/*` directory.
2. Follow the deployment steps in the `examples/amazon-bedrock-multi-agent-collaboration/*/README.md` file of the example.

## Examples

To get you started working with Bedrock multi-agent collaboration, we provide the following examples:

- **[Hello World](/examples/multi-agent-collaboration/00_hello_world_agent/)**: This example is a great way to get started! Bare bones example showing minimal lines of code to have a working supervisor and
collaborator.

- **[DevOps Assistant](/examples/multi-agent-collaboration/devops_agent/)**: The DevOps assistant helps DevOps engineers by acting as the coordinator between code changes and system status by correlating GitHub activities with real-time infrastructure metrics from Grafana. By orchestrating between these two domains, it can proactively identify potential issues (like a problematic PR that might impact system health) and suggest preventive actions, providing end-to-end visibility and automated decision support across the development and operations lifecycle.

- **[Energy Efficiency Management](/examples/multi-agent-collaboration/energy_efficiency_management_agent/)**: The Energy Efficiency Assistant acts as an energy management orchestrator, combining forecasting insights, solar panel maintenance instructions, and peak load management to provide users with a holistic view of their energy ecosystem. By coordinating between these specialized agents, it delivers personalized recommendations, with consumption patterns and device usage, helping customers optimize their energy habits.

- **[Mortgage Assistant Agent](/examples/multi-agent-collaboration/mortgage_assistant/)**: This example demonstrates the use of Amazon Bedrock Agents multi-agent collaboration with its built-in Routing Classifier feature. By simply enabling that mode for your supervisor, Bedrock automatically routes to the correct collaborating sub-agent using LLM intent classification optimized to route with sub-second latency. Contrast that with a traditional supervisor that must go through its own orchestration loop, a more expensive proposition that can take 3-6 seconds depending on which LLM you are using. This feature is most valuable when trying to build a unified customer experience across a set of sub-agents. In our example, we have 3 collaborators: one for general mortgage questions, one for handling conversations about Existing mortgages, and another for dealing with New mortgages.

- **[Portfolio Assistant](/examples/multi-agent-collaboration/portfolio_assistant_agent/)** Portfolio Assistant has three collaborators, a News agent, a Stock Data agent, and a Financial Analyst. These specialists are orchestrated to perform investment analysis for a given stock ticker based on the latest news and recent stock price movements.

- **[Startup Advisor](/examples/multi-agent-collaboration/startup_advisor_agent/)** Have a new startup in mind, but haven't quite hired your marketing staff? Use the Startup Advisor to do your market research, come up with campaign ideas, write effective campaign copy, and get a comprehensive Markdown-formatted report. It uses a set of 5 collaborating sub-agents to get the job done, including: Lead Market Analyst, Content Creator, Creative Director, Chief Stategist, and Formatted Report Writer.

- **[Sports Team Poet](/examples/multi-agent-collaboration/team_poems_agent/)** This is a fun example for sports fans. The Sports Team Poet is a supervisor with a Sports Researcher and a Sports Poetry Writer. Pick your favorite team (go Celtics!) and see multi-agents collaborate to conduct web searches about your team and make a fun poem based on those insights. Have fun!

- **[Trip Planner](/examples/multi-agent-collaboration/trip_planner_agent/)** The Trip Planner uses three sub-agents to help you build a robust itinerary. It leverages a Restaurant Scout and an Activity Finder to get great ideas, and an Itinerary Compiler to finish the job. Try it out for your next trip.

- **[Voyage Virtuoso Agent](/examples/multi-agent-collaboration/voyage_virtuoso_agent/)** Dream big with the Voyage Virtuoso, a supervisor agent that is built for high net worth individuals that need help picking the most expensive and elaborate destinations given a theme ("I want to ski on expert slopes, and I need a ski-on/ski-off resort with great night life. Don't disappoint!").

- **[Mortgage Assistant](/examples/multi-agent-collaboration/mortgage_assistant/)** This example demonstrates the use of Bedrock's built-in Routing Classifier. By simply enabling that mode for your supervisor, Bedrock automatically routes to the correct collaborating sub-agent using LLM intent classification optimized to route with sub-second latency. Have conversations with sub-agents about existing mortgages, new mortgages and
general questions about mortgages like when to refinance or choosing between 15-year and 30-year mortgages.