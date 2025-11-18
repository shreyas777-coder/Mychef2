#Welcome to Ulitmate Chef ! This is the starter repository where you'll build a production-ready ADK agent step by step.

## 🚀 What You'll Build
1. **Deploy Gemma to Cloud Run with GPU** - Set up a high-performance Gemma model backend
2. **Integrate the Gemma deployment with an ADK agent** - Connect your agent to the GPU-accelerated model
3. **Test with ADK Web interface** - Validate your conversational agent works correctly
4. **Perform load testing** - Observe how both Cloud Run instances auto-scale under load

## 📁 Starter Structure

```
Mychef2/
├── README.md                    # This file
├── ollama-backend/              # Ollama backend 
│   └── Dockerfile               # Backend container 
└── adk-agent/                   # ADK agent 
    ├── pyproject.toml           # Python dependencies 
    ├── env.template             # Environment template 
    ├── server.py                # FastAPI server 
    ├── Dockerfile               # Container config 
    ├── elasticity_test.py       # Elasticity testing 
    └── production_agent/        # Agent implementation
        ├── __init__.py          # Package init 
        └── agent.py             # Agent logic 
```

## 🎯 Files to Complete

You'll need to implement the following files by following the codelab instructions:

**Ollama Backend:**

- 🚧 `ollama-backend/Dockerfile` - Ollama container

**ADK Agent:**

- ✅ `adk-agent/pyproject.toml` - Dependencies (already complete)
- ✅ `adk-agent/env.template` - Environment template (already complete)
- 🚧 `adk-agent/production_agent/agent.py` - ADK agent implementation
- 🚧 `adk-agent/server.py` - FastAPI server with endpoints
- 🚧 `adk-agent/Dockerfile` - Container configuration
- 🚧 `adk-agent/elasticity_test.py` - Elasticity testing script

## 📚 Getting Started

1. Follow the instructions
2. Copy and paste the provided commands
3. Deploy Gemma backend to Cloud Run with GPU
4. Deploy ADK agent and test with elasticity testing

## 🔗 Resources

- [Google ADK Documentation](https://cloud.google.com/agent-development-kit)
- [Cloud Run Documentation](https://cloud.google.com/run/docs)
