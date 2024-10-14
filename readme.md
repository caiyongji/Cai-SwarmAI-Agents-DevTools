Cai-SwarmAI-Agents-DevTools  
A showcase of AI agents developed by Cai using OpenAI Swarm to generate PRDs and Cursor instructions.

# Commands

## create conda env
> :bangbang: Notice: As of **October 14, 2024**, OpenAI Swarm only supports up to `Python 3.12`.

```bash
conda create --name cai_2024 python=3.12
conda activate cai_2024
pip install git+ssh://git@github.com/openai/swarm.git
```


Here’s a more polished version in a programming documentation style:

---

### Setting Up SSH Keys on GitHub (If You Don’t Have One)
1. Generate a new SSH key by running the following command:
   ```bash
   ssh-keygen -t ed25519 -C "your_email@example.com"
   ```
2. Copy the public key to your clipboard:
   ```bash
   pbcopy < ~/.ssh/id_ed25519.pub
   ```
3. Add the public key to your GitHub account by navigating to [SSH and GPG keys](https://github.com/settings/keys) and pasting it there.
---


## install dotenv
```bash
pip install python-dotenv
```
