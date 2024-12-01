# Startup Advisor Agent

Have a new startup in mind, but haven't quite hired your marketing staff? Use this Startup Advisrt agent to do your market research, come up with campaign ideas, and write effective campaign copy. It uses a set of 5 sub-agents to get the job done these include Lead Market Analyst, Content Creator, Chief Conent Creator, Chief Stategist, and Agent Storage Manager.

![architecture]

## Prerequisites

1. Clone and install repository

```bash
git clone https://github.com/awslabs/amazon-bedrock-agent-samples

cd amazon-bedrock-agent-samples

python3 -m venv .venv

source .venv/bin/activate

pip3 install -r src/requirements.txt
```

2. Deploy web_seach tool

Follow instructions [here](/src/shared/web_search/).

3. Deploy working memory tool

Follow instructions [here](/src/shared/working_memory/).

## Usage & Sample Prompts


1. Deploy Amazon Bedrock Agents

```bash
python3 examples/amazon-bedrock-multi-agent-collaboration/startup_advisor_agent/main.py --recreate_agents "true"
```

2. Invoke

```bash
python3 examples/amazon-bedrock-multi-agent-collaboration/voyage_virtuoso_agent/main.py --recreate_agents "false" --voyage ""Give me some great options for skip trip for an expert and with ski-on/ski-off townhouse"
```

3. Cleanup

```bash
python3 examples/amazon-bedrock-multi-agent-collaboration/voyage_virtuoso_agent/main.py --clean_up "true"
```

## License

This project is licensed under the Apache-2.0 License.