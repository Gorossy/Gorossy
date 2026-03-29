![Your Company Banner](https://user-images.githubusercontent.com/49298926/260277996-a8298f3a-d09f-4f61-8d85-29f5bc21599b.png)

# Hi, I'm David Maldonado 👋

## AI-Assisted Full Stack Developer | Senior Backend & Infrastructure Engineer | Python · Django · FastAPI | Cloud Infrastructure | Blockchain | AI/ML Infrastructure | GPU Computing | Bittensor | Docker | Kubernetes | Top Rated Plus Upwork

Welcome to my GitHub! I'm a Systems and Computer Engineer based in **Bogotá, Colombia**, with 4+ years of experience building scalable backend systems, cloud infrastructure, and AI-integrated applications across tourism, insurance, fintech, e-commerce, marketing and blockchain industries.

### 🚀 Key Achievements
 
- **800x API Latency Reduction**: Designed and deployed a 6-node Redis Cluster on GCP that reduced API response times from **2,400ms → 3–5ms**, eliminating a critical bottleneck in a distributed GPU computing platform.
- **Open Source Contributor — Bittensor SN27**: Created and maintained the automated miner installation system for Bittensor's ni-compute subnet (**60 stars, 43 forks**), used by hundreds of developers to deploy GPU resources for AI workloads.
- **Startup Founder — Ucover**: Co-founded and led Ucover as CTO, building a full B2B2C marketplace with real-time inventory management, Mercado Pago payment integration, and business analytics dashboards. Won two entrepreneurship competitions and secured **$10K in pre-seed funding** among 220 competing companies.
- **Top Rated Plus on Upwork**: Highest freelancer status, reflecting consistent delivery and client satisfaction across 4+ years on the platform.

### 🛠️ Technologies and Tools

**Languages**: Python, JavaScript, Go, Bash/Shell

**Backend Frameworks**: Django, Django REST Framework, FastAPI, Flask

**Cloud & DevOps**: GCP, AWS (S3, EC2, RDS), Docker, Kubernetes, Terraform, CI/CD, GitHub Actions

**AI/ML Infrastructure**: vLLM, Hugging Face, PyTorch, Jupyter Notebooks, GPU Computing (NVIDIA CUDA), LLM Deployment, Ollama, ComfyUI

**Blockchain & Distributed Systems**: Bittensor, Ethereum, Distributed Mining & Validation Systems, Consensus Protocols, Validator-Miner Architecture

**Databases**: PostgreSQL, MongoDB, Firebase

**Testing & QA**: Pytest, Postman, End-to-End Testing, Unit Testing

**Architecture**: Microservices, Ports and Adapters, RESTful APIs, Distributed Systems

---
 
### 🌟 Projects
 
#### 🎯 [Ucover](https://ucoverapp.com) — B2B2C Tourism Marketplace
The Airbnb of local experiences in Colombia. Hosts manage inventory, capacity, and revenue analytics through a SaaS dashboard while users discover and book experiences with guaranteed payments.
 
- **Stack**: Django REST Framework · PostgreSQL · React + Vite · AWS EC2/S3 · Docker · Vercel
- **Highlights**: Concurrent inventory management to prevent overbooking, async Mercado Pago webhook integration (auto-confirm reservations + email receipts), JWT via HttpOnly cookies (XSS/CSRF protection), SQL aggregation dashboards with revenue metrics and occupancy alerts, APScheduler for automatic slot cleanup.
 
#### 🎓 [Rótalo](https://www.rotalo.xyz) — University Super-App
Colombian university platform for schedule management, carpooling, and anonymous community walls. AI reads uploaded PDFs/images to extract class schedules and power peer matching.
 
- **Stack**: FastAPI · PostgreSQL · Redis · Docker · AWS EC2 · Next.js · Vercel
- **Highlights**: AI-powered schedule parsing (PDF/image), shared-ride matching by entry/exit time, privacy-preserving design (never exposes class details to other users), anonymous confession walls per university.
 
#### 🐳 [LLM WebUI Docker Templates](https://github.com/Gorossy/docker_llama) — One-command LLM Deployment
Production-ready Docker images for running large language models locally or on GPU cloud (Hyperstack), combining vLLM inference + Open WebUI + SSH access orchestrated via s6-overlay.
 
- **Stack**: Docker · vLLM · Open WebUI · NVIDIA CUDA · s6-overlay · HuggingFace
- **Published images** (`docker pull` ready):
 
| Image | Model | VRAM |
|---|---|---|
| `dmaldonadob/llm-webui-deepseek-r1-14b` | DeepSeek-R1-Distill-Qwen-14B | 16GB+ |
| `dmaldonadob/llm-webui-qwen3-8b` | Qwen3 8B | 16GB+ |
| `dmaldonadob/llm-webui-qwen3-32b` | Qwen3 32B | 40GB+ |
| `dmaldonadob/llm-webui` | Generic (configurable via env) | — |
| `dmaldonadob/ssh-base-pytorch-cuda` | Base CUDA image | — |
 
- **Highlights**: s6-overlay dependency chain (SSH → vLLM → WebUI), persistent HuggingFace model cache via volume mounts, fully configurable via env vars (`VLLM_MODEL`, `VLLM_GPU_MEMORY_UTILIZATION`), validated on Hyperstack A100/H100 GPU nodes.
 
#### 💇 Rezzy — Salon Management Platform *(Private)*
Multi-tenant booking system for salons and barbershops with real-time availability and appointment scheduling.
 
- **Stack**: Django · PostgreSQL · React Native
- *Not publicly available due to multi-founder agreement.*
 
---
 
### 🌱 Open Source Contributions
 
- **Bittensor Subnet 27 (SN27)**: Multiple approved PRs to core infrastructure — validator-miner communication, template system, and feature development.
- **Enterprise GPU Templates**: 8+ containerized environments published to Docker Hub (PyTorch, Miniconda, Jupyter, Ollama, ComfyUI, vLLM, Automatic1111) [LINK](https://hub.docker.com/repositories/dmaldonadob) .
- **LLM WebUI Templates**: Multi-service Docker images bundling vLLM + Open WebUI for DeepSeek R1, Qwen3 8B/32B and other frontier models — tested on Hyperstack GPU infrastructure.
- **Technical Documentation**: Authored release notes and deployment docs for SN27 subnet versions v2.2.0 through v2.3.2.
 
---
 
### 📫 Let's Connect
 
- **LinkedIn**: [David Maldonado](https://www.linkedin.com/in/dmaldonadob/)
- **Upwork**: [Top Rated Plus Profile](https://www.upwork.com/freelancers/~01f71d13c4db8160c6)
- **Docker Hub**: [dmaldonadob](https://hub.docker.com/repositories/dmaldonadob)
 
---
 
⭐️ Thanks for stopping by — feel free to explore the repos or reach out to collaborate.
 
