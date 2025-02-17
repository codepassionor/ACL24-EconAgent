# EconAI: Dynamic Persona Evolution and Memory-Aware Agents in Evolving Economic Environments

It's based on [Foundation](https://github.com/MaciejMacko/ai-economist) and [EconAgent](https://github.com/tsinghua-fib-lab/ACL24-EconAgent/), An Dynamic Persona Evolution and Memory-Aware Economic Simulation Framework


# Run
To run simulations with GPT-3.5, using 100 agents over 240 months, ensure the `openai.api_key` is filled in `simulate_utils.py` and then execute the following command:

`python simulate.py --policy_model gpt --num_agents 100 --episode_length 240`

To run simulations with the Composite model, also with 100 agents and 240 months, use this command:

`python simulate.py --policy_model complex --num_agents 100 --episode_length 240`

For reinforcement learning approaches, such as **The AI Economist**, you can follow their training code and use the pretrained models for simulations. Refer to the appendix in the paper for further details.
