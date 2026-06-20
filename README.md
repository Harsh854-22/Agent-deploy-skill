# InferNet Agent Deployer & Integrator Skill

A standardized **Agent Skill** designed to configure AI agents (such as Claude and ChatGPT) as an elite **InferNet Architect** specializing in the InferNet P2P Agent Sharing Protocol.

---

## 🚀 Overview

**InferNet** is a peer-to-peer marketplace where anyone can host a local AI agent and get paid per call. This repository packages the system prompt, guidelines, and context required for an AI assistant to help developers deploy, monetize, and discover agents using the `infernet` Python SDK, libp2p networking, and the Monad blockchain.

---

## 🛠️ Repository Structure

* **`SKILL.md`**: Contains the core Agent Skill configuration, including YAML metadata and the system instruction prompt.

---

## 📖 How to Use

### 1. With ChatGPT (Using Web Search)
You can instruct ChatGPT to read this repository directly in a single prompt:
> *"Search the web for the GitHub repository `Harsh854-22/Agent-deploy-skill`, read the `SKILL.md` file, and adopt the role of the InferNet Architect to help me write a custom Python agent."*

### 2. With Claude (e.g. Claude Code / Claude Desktop)
Since Claude natively supports the Agent Skills open standard, you can load this skill directly during a chat session:
```bash
/learn https://github.com/Harsh854-22/Agent-deploy-skill
```

### 3. As a Custom GPT
1. Go to **Explore GPTs** -> **Create** in ChatGPT.
2. Under the **Configure** tab, paste the contents of `SKILL.md` (excluding the YAML frontmatter delimiters) into the **Instructions** text box.
3. Save and publish.

---

## ⚡ Submission to Marketplace

This repository is fully compatible with **agentskill.sh**. To list it in the public index:
1. Navigate to [agentskill.sh/submit](https://agentskill.sh/submit).
2. Paste the repository URL: `https://github.com/Harsh854-22/Agent-deploy-skill`.
3. Submit the form to register it.
