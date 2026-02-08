# Awesome DevOps MCP Servers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome Model Context Protocol (MCP) servers focused on DevOps tools and capabilities.

## What is MCP?

[MCP](https://modelcontextprotocol.io/) is an open protocol that enables AI models to securely interact with local and remote resources through standardized server implementations. This list focuses on DevOps-related MCP servers that extend AI capabilities through cloud infrastructure management, CLI operations, version control, security scanning, and other DevOps-related services.

## Related Resources

- [awesome](https://github.com/sindresorhus/awesome#readme) - Awesome lists about all kinds of interesting topics.
- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers/) - A comprehensive list of all MCP servers.
- [awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients/) - A list of MCP clients.

## Legend

- 🎖️ – official implementation
- programming language
  - 🐍 – Python codebase
  - 📇 – TypeScript (or JavaScript) codebase
  - 🏎️ – Go codebase
  - 🦀 – Rust codebase
  - #️⃣ - C# Codebase
  - ☕ - Java codebase
- scope
  - ☁️ - Cloud Service
  - 🏠 - Local Service
  - 📟 - Embedded Systems
- operating system
  - 🍎 – For macOS
  - 🪟 – For Windows
  - 🐧 - For Linux

## Server Implementations

## Cloud Infrastructure

### 🏗️ Infrastructure as Code
Tools for managing infrastructure through code, including Terraform, Pulumi, and other IaC platforms.

- [dulltz/mcp-server-hcp-terraform](https://github.com/dulltz/mcp-server-hcp-terraform) 🐍 ☁️ - MCP server for working with HashiCorp Cloud Platform (HCP) Terraform, enabling AI assistants to interact with Terraform Cloud resources.
- [guilhermeyoshida/mcp-terraform-assistant](https://github.com/guilhermeyoshida/mcp-terraform-assistant) 🐍 🏠 - An MCP server for managing infrastructure as code using Terraform.
- [jashkahar/Terraform-MCP-Server](https://github.com/jashkahar/Terraform-MCP-Server) 🐍 ☁️ - This project provides an MCP server that exposes Terraform infrastructure-as-code operations through natural language.
- [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp) 🦀 🏠 - A Terraform MCP server allowing AI assistants to manage and operate Terraform environments, enabling reading configurations, analyzing plans, applying configurations, and managing Terraform state.
- [pulumi/mcp-server](https://github.com/pulumi/mcp-server) 🎖️ 📇 🏠 - MCP server for interacting with Pulumi using the Pulumi Automation API and Pulumi Cloud API. Enables MCP clients to perform Pulumi operations like retrieving package information, previewing changes, deploying updates, and retrieving stack outputs programmatically.
- [severity1/terraform-cloud-mcp](https://github.com/severity1/terraform-cloud-mcp) 🐍 ☁️ - A Model Context Protocol server that integrates AI assistants with the Terraform Cloud API, allowing you to manage your infrastructure.
- [thrash888/terraform-mcp-server](https://github.com/thrash888/terraform-mcp-server) 📇 ☁️ - Terraform Registry MCP Server for interacting with Terraform registries.
- [westonplatter/mcp-terraform-python](https://github.com/westonplatter/mcp-terraform-python) 🐍 🏠 - MCP server to run terraform operations locally.
- [stakpak/mcp](https://github.com/stakpak/mcp) 🦀 - MCP Server for interacting, editing and generating code for Terraform, Kubernetes, GithubActions and Dockerfile.

### 🐳 Container Orchestration
Tools for managing containers, Kubernetes clusters, and related orchestration platforms.

- [rohitg00/kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server) 🐍 ☁️/🏠 - A Model Context Protocol (MCP) server for Kubernetes that enables AI assistants like Claude, Cursor, and others to interact with Kubernetes clusters through natural language.
- [alexei-led/k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server) 🐍 🏠 - A lightweight yet robust server that empowers AI assistants to securely execute Kubernetes CLI commands (`kubectl`, `helm`, `istioctl`, and `argocd`) using Unix pipes in a safe Docker environment with multi-architecture support.
- [Flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) 📇 ☁️/🏠 - Typescript implementation of Kubernetes cluster operations for pods, deployments, services.
- [manusa/kubernetes-mcp-server](https://github.com/manusa/kubernetes-mcp-server) 🏎️ 🏠 - A powerful Kubernetes MCP server with additional support for OpenShift. Besides providing CRUD operations for any Kubernetes resource, this server provides specialized tools to interact with your cluster.
- [portainer/portainer-mcp](https://github.com/portainer/portainer-mcp) 🏎️ ☁️/🏠 - A powerful MCP server that enables AI assistants to seamlessly interact with Portainer instances, providing natural language access to container management, deployment operations, and infrastructure monitoring capabilities.
- [rohitg00/kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server) 🐍 ☁️/🏠 - A Model Context Protocol (MCP) server for Kubernetes that enables AI assistants like Claude, Cursor, and others to interact with Kubernetes clusters through natural language.
- [rrmistry/tilt-mcp](https://github.com/rrmistry/tilt-mcp) 🐍 🏠 🍎 🪟 🐧 - Model Context Protocol server that integrates with Tilt to provide programmatic access to Tilt resources, logs, and management operations for Kubernetes development environments.
- [strowk/mcp-k8s-go](https://github.com/strowk/mcp-k8s-go) 🏎️ ☁️/🏠 - Kubernetes cluster operations through MCP.
- [weibaohui/k8m](https://github.com/weibaohui/k8m) 🏎️ ☁️/🏠 - Provides MCP multi-cluster Kubernetes management and operations, featuring a management interface, logging, and nearly 50 built-in tools covering common DevOps and development scenarios. Supports both standard and CRD resources.
- [weibaohui/kom](https://github.com/weibaohui/kom) 🏎️ ☁️/🏠 - Provides MCP multi-cluster Kubernetes management and operations. It can be integrated as an SDK into your own project and includes nearly 50 built-in tools covering common DevOps and development scenarios. Supports both standard and CRD resources.
- [wenhuwang/mcp-k8s-eye](https://github.com/wenhuwang/mcp-k8s-eye) 🏎️ ☁️/🏠 - MCP Server for kubernetes management, and analyze your cluster, application health.
- [kocierik/mcp-nomad](https://github.com/kocierik/mcp-nomad) 🏎️ ☁️/🏠 - MCP Server for nomad management, and analyze your cluster, application health, logs and ACL.
- [aadarshjain/kubectl-mcp-server](https://github.com/aadarshjain/kubectl-mcp-server) 🐍 🏠 - A STDIO based MCP server for Kubernetes that interacts seamlessly with your local clusters (~/.kube/config) using `kubectl` CLI commands. Uses read-only operations by default to prevent accidental modifications/deletion of K8s resources.

### ☁️ Cloud Providers

#### AWS
- [awslabs/mcp](https://github.com/awslabs/mcp) 🎖️ 🐍 ☁️ - Official AWS MCP server for interacting with AWS services using the Model Context Protocol. Enables AI assistants to manage AWS resources through natural language and programmatic interfaces.
- [alexei-led/aws-mcp-server](https://github.com/alexei-led/aws-mcp-server) 🐍 ☁️ - A lightweight but powerful server that enables AI assistants to execute AWS CLI commands, use Unix pipes, and apply prompt templates for common AWS tasks in a safe Docker environment with multi-architecture support.

#### Azure
- [aaronsb/ado-mcp](https://github.com/aaronsb/ado-mcp) 📇 ☁️ - Azure DevOps MCP Server for integrating AI assistants with Azure DevOps services.
- [erikhoward/adls-mcp-server](https://github.com/erikhoward/adls-mcp-server) 🐍 ☁️/🏠 - MCP Server for Azure Data Lake Storage. It can perform manage containers, read/write/upload/download operations on container files and manage file metadata.
- [hardik-id/azure-resource-graph-mcp-server](https://github.com/hardik-id/azure-resource-graph-mcp-server) 📇 ☁️/🏠 - A Model Context Protocol server for querying and analyzing Azure resources at scale using Azure Resource Graph, enabling AI assistants to explore and monitor Azure infrastructure.
- [jdubois/azure-cli-mcp](https://github.com/jdubois/azure-cli-mcp) 🐍 ☁️ - A wrapper around the Azure CLI command line that allows you to talk directly to Azure.
- [stefanskiasan/azure-devops-mcp-server](https://github.com/stefanskiasan/azure-devops-mcp-server) 📇 ☁️ - MCP Server for Cline to Access Azure DevOps.
- [Tiberriver256/mcp-server-azure-devops](https://github.com/Tiberriver256/mcp-server-azure-devops) 📇 ☁️ - Azure DevOps integration for repository management, work items, and pipelines.
- [Vortiago/mcp-azure-devops](https://github.com/Vortiago/mcp-azure-devops) 📇 ☁️ - A Model Context Protocol server enabling AI assistants to interact with Azure DevOps services via Python SDK.

#### Alibaba Cloud
- [aliyun/alibaba-cloud-ops-mcp-server](https://github.com/aliyun/alibaba-cloud-ops-mcp-server) 🎖️ 🐍 ☁️ - A MCP server that enables AI assistants to operation resources on Alibaba Cloud, supporting ECS, Cloud Monitor, OOS and widely used cloud products.

#### Other Cloud Platforms
- [bright8192/esxi-mcp-server](https://github.com/bright8192/esxi-mcp-server) 🐍 ☁️ - A VMware ESXi/vCenter management server based on MCP (Model Control Protocol), providing simple REST API interfaces for virtual machine management.
- [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) 🎖️ 📇 ☁️ - Integration with Cloudflare services including Workers, KV, R2, and D1.
- [thunderboltsid/mcp-nutanix](https://github.com/thunderboltsid/mcp-nutanix) 🏎️ 🏠/☁️ - Go-based MCP Server for interfacing with Nutanix Prism Central resources.

### 🖥️ Command Line
Run commands, capture output and otherwise interact with shells and command line tools.

- [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) 🖥️ 🛠️ 💬 - A Model Context Protocol server that provides access to iTerm. You can run commands and ask questions about what you see in the iTerm terminal.
- [g0t4/mcp-server-commands](https://github.com/g0t4/mcp-server-commands) 📇 🏠 - Run any command with `run_command` and `run_script` tools.
- [maxim-saplin/mcp_safe_local_python_executor](https://github.com/maxim-saplin/mcp_safe_local_python_executor) - Safe Python interpreter based on HF Smolagents `LocalPythonExecutor`
- [MladenSU/cli-mcp-server](https://github.com/MladenSU/cli-mcp-server) 🐍 🏠 - Command line interface with secure execution and customizable security policies
- [OthmaneBlial/term_mcp_deepseek](https://github.com/OthmaneBlial/term_mcp_deepseek) 🐍 🏠 - A DeepSeek MCP-like Server for Terminal
- [tumf/mcp-shell-server](https://github.com/tumf/mcp-shell-server) - A secure shell command execution server implementing the Model Context Protocol (MCP)
- [automateyournetwork/pyATS_MCP](https://github.com/automateyournetwork/pyATS_MCP) - Cisco pyATS server enabling structured, model-driven interaction with network devices.
- [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) 📇 🏠 🍎 🪟 🐧 - A swiss-army-knife that can manage/execute programs and read/write/search/edit code and text files.

### 🔄 Version Control
Interact with Git repositories and version control platforms. Enables repository management, code analysis, pull request handling, issue tracking, and other version control operations through standardized APIs.

- [adhikasp/mcp-git-ingest](https://github.com/adhikasp/mcp-git-ingest) 🐍 🏠 - Read and analyze GitHub repositories with your LLM
- [ddukbg/github-enterprise-mcp](https://github.com/ddukbg/github-enterprise-mcp) 📇 ☁️ 🏠 - MCP server for GitHub Enterprise API integration
- [gitea/gitea-mcp](https://gitea.com/gitea/gitea-mcp) 🎖️ 🏎️ ☁️ 🏠 🍎 🪟 🐧 - Interactive with Gitea instances with MCP.
- [github/github-mcp-server](https://github.com/github/github-mcp-server) 📇 ☁️ - Official GitHub server for integration with repository management, PRs, issues, and more.
- [kopfrechner/gitlab-mr-mcp](https://github.com/kopfrechner/gitlab-mr-mcp) 📇 ☁️ - Interact seamlessly with issues and merge requests of your GitLab projects.
- [modelcontextprotocol/server-git](https://github.com/modelcontextprotocol/servers/tree/main/server-git) 🐍 🏠 - Direct Git repository operations including reading, searching, and analyzing local repositories
- [modelcontextprotocol/server-gitlab](https://github.com/modelcontextprotocol/servers/tree/main/server-gitlab) 📇 ☁️ 🏠 - GitLab platform integration for project management and CI/CD operations
- [oschina/mcp-gitee](https://github.com/oschina/gitee) 🏎️ ☁️ 🏠 - Gitee API integration, repository, issue, and pull request management, and more.
- [Tiberriver256/mcp-server-azure-devops](https://github.com/Tiberriver256/mcp-server-azure-devops) 📇 ☁️ - Azure DevOps integration for repository management, work items, and pipelines.

### 🔒 Security
MCP servers for security operations, vulnerability scanning, and threat detection.

- [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) ☕ 🏠 - A Model Context Protocol server for Ghidra that enables LLMs to autonomously reverse engineer applications. Provides tools for decompiling binaries, renaming methods and data, and listing methods, classes, imports, and exports.
- [13bm/GhidraMCP](https://github.com/13bm/GhidraMCP) 🐍 ☕ 🏠 - MCP server for integrating Ghidra with AI assistants. This plugin enables binary analysis, providing tools for function inspection, decompilation, memory exploration, and import/export analysis via the Model Context Protocol.
- [BurtTheCoder/mcp-shodan](https://github.com/BurtTheCoder/mcp-shodan) 📇 🪟 ☁️ - MCP server for querying the Shodan API and Shodan CVEDB. This server provides tools for IP lookups, device searches, DNS lookups, vulnerability queries, CPE lookups, and more.
- [BurtTheCoder/mcp-virustotal](https://github.com/BurtTheCoder/mcp-virustotal) 📇 🪟 ☁️ - MCP server for querying the VirusTotal API. This server provides tools for scanning URLs, analyzing file hashes, and retrieving IP address reports.
- [fr0gger/MCP_Security](https://github.com/fr0gger/MCP_Security) 📇 ☁️ - MCP server for querying the ORKL API. This server provides tools for fetching threat reports, analyzing threat actors, and retrieving intelligence sources.
- [girste/mcp-cybersec-watchdog](https://github.com/girste/mcp-cybersec-watchdog) 🐍 🏠 🐧 - Comprehensive security audit tool for Linux servers. Analyzes firewall, SSH hardening, threats, fail2ban, Docker, kernel hardening. Returns actionable recommendations with zero configuration.
- [qianniuspace/mcp-security-audit](https://github.com/qianniuspace/mcp-security-audit) 📇 ☁️ - A powerful MCP (Model Context Protocol) Server that audits npm package dependencies for security vulnerabilities. Built with remote npm registry integration for real-time security checks.
- [semgrep/mcp](https://github.com/semgrep/mcp) 📇 ☁️ - Allow AI agents to scan code for security vulnerabilites using [Semgrep](https://semgrep.dev).
- [slouchd/cyberchef-api-mcp-server](https://github.com/slouchd/cyberchef-api-mcp-server) 🐍 ☁️ - MCP server for interacting with the CyberChef server API which will allow an MCP client to utilise the CyberChef operations.
- [rad-security/mcp-server](https://github.com/rad-security/mcp-server) 📇 ☁️ - MCP server for RAD Security, providing AI-powered security insights for Kubernetes and cloud environments. This server provides tools for querying the Rad Security API and retrieving security findings, reports, runtime data and many more.
- [securityfortech/secops-mcp](https://github.com/securityfortech/secops-mcp) 🐍 🏠 - All-in-one security testing toolbox that brings together popular open source tools through a single MCP interface. Connected to an AI agent, it enables tasks like pentesting, bug bounty hunting, threat hunting, and more.
- [roadwy/cve-search_mcp](https://github.com/roadwy/cve-search_mcp) 🐍 🏠 - A Model Context Protocol (MCP) server for querying the CVE-Search API. This server provides comprehensive access to CVE-Search, browse vendor and product、get CVE per CVE-ID、get the last updated CVEs.
- [nickpending/mcp-recon](https://github.com/nickpending/mcp-recon) 🏎️ 🏠 - Conversational recon interface and MCP server powered by httpx and asnmap. Supports various reconnaissance levels for domain analysis, security header inspection, certificate analysis, and ASN lookup.

## CI/CD & DevOps Pipelines

### 🔄 Continuous Integration
Tools for automating the integration of code changes and running tests.

- [Tiberriver256/mcp-server-github-actions](https://github.com/Tiberriver256/mcp-server-github-actions) 📇 ☁️ - MCP server for interacting with GitHub Actions workflows, enabling AI assistants to manage CI/CD pipelines.
- [lobehub/mcp-hello-world](https://github.com/lobehub/mcp-hello-world) 📇 ☁️ - A simple Hello World MCP server for CI/CD test.

### 📱 Mobile CI/CD
Tools specifically designed for mobile application CI/CD pipelines.

- [stefanoamorelli/codemagic-mcp](https://github.com/stefanoamorelli/codemagic-mcp) 🐍 ☁️ - Codemagic CI/CD MCP Server for mobile app CI/CD pipeline management.

### 🔄 DevOps Visibility
Tools for providing visibility across the entire DevOps lifecycle.

- [SBDI/mcp-devps-hub](https://github.com/SBDI/mcp-devps-hub) 🐍 🏠 - MCP server for end-to-end development visibility (Jira, GitHub, CI/CD, etc.).
- [Acid-base/FastMCP-Proper](https://github.com/Acid-base/FastMCP-Proper) 🐍 🏠 - Python MCP server with CI/CD tooling and testability built-in.
- [gofireflyio/firefly-mcp](https://github.com/gofireflyio/firefly-mcp) 🎖️ 📇 ☁️ - Integrates, discovers, manages, and codifies cloud resources with [Firefly](https://firefly.ai).

### 👨‍💻 Code Execution
Code execution servers. Allow LLMs to execute code in a secure environment.

- [pydantic/pydantic-ai/mcp-run-python](https://github.com/pydantic/pydantic-ai/tree/main/packages/mcp-run-python) 🐍 🏠- Run Python code in a secure sandbox via MCP tool calls
- [yepcode/mcp-server-js](https://github.com/yepcode/mcp-server-js) 🎖️ 📇 ☁️ - Execute any LLM-generated code in a secure and scalable sandbox environment and create your own MCP tools using JavaScript or Python, with full support for NPM and PyPI packages
- [ckanthony/openapi-mcp](https://github.com/ckanthony/openapi-mcp) 🏎️ ☁️ - OpenAPI-MCP: Dockerized MCP Server to allow your AI agent to access any API with existing api docs.
- [alfonsograziano/node-code-sandbox-mcp](https://github.com/alfonsograziano/node-code-sandbox-mcp) 📇 🏠 – A Node.js MCP server that spins up isolated Docker-based sandboxes for executing JavaScript snippets with on-the-fly npm dependency installation and clean teardown

### 🤖 Coding Agents
Full coding agents that enable LLMs to read, edit, and execute code and solve general programming tasks completely autonomously.

- [bgauryy/octocode-mcp](https://github.com/bgauryy/octocode-mcp) ☁️ 📇 🍎 🪟 🐧 - AI-powered developer assistant that enables advanced research, analysis and discovery across GitHub ecosystem
- [oraios/serena](https://github.com/oraios/serena) 🐍🏠 - A fully-featured coding agent that relies on symbolic code operations by using language servers.
- [ezyang/codemcp](https://github.com/ezyang/codemcp) 🐍🏠 - Coding agent with basic read, write and command line tools.
-   - [Wolfe-Jam/claude-faf-mcp](https://github.com/Wolfe-Jam/claude-faf-mcp)
  📇 🏠 - First & only persistent project context MCP. Provides .faf (Foundational AI-context Format) Project DNA with 33+ tools, Podium scoring (0-100%), and format-driven architecture. Official Anthropic Registry. 10k+ npm downloads.
- [doggybee/mcp-server-leetcode](https://github.com/doggybee/mcp-server-leetcode) 📇 ☁️ - An MCP server that enables AI models to search, retrieve, and solve LeetCode problems. Supports metadata filtering, user profiles, submissions, and contest data access.
- [jinzcdev/leetcode-mcp-server](https://github.com/jinzcdev/leetcode-mcp-server) 📇 ☁️ - MCP server enabling automated access to LeetCode's programming problems, solutions, submissions and public data with optional authentication for user-specific features (e.g., notes), supporting both `leetcode.com` (global) and `leetcode.cn` (China) sites.
- [juehang/vscode-mcp-server](https://github.com/juehang/vscode-mcp-server) 📇 🏠 - A MCP Server that allows AI such as Claude to read from the directory structure in a VS Code workspace, see problems picked up by linter(s) and the language server, read code files, and make edits.
- [scrapeless/mcp-server-scrapeless](https://github.com/scrapeless-ai/scrapeless-mcp-server) 📇☁️🍎🪟🐧 - Seamlessly integrate real-time Google SERP(Google Search, Google Flight, Google Map, Google Jobs....) results into your LLM applications using the Scrapeless MCP server.

### 🔗 Aggregators
Servers for accessing many apps and tools through a single MCP server.

- [askbudi/roundtable](https://github.com/askbudi/roundtable) 🐍 🏠 - Zero-configuration MCP server that unifies multiple AI coding assistants (Codex, Claude Code, Cursor, Gemini) through intelligent auto-discovery and standardized interface.
- [Composiohq/Rube](https://github.com/composiohq/rube) - Rube is an MCP server built on the Composio integration platform. It connects your AI tools to 500+ apps.
- [julien040/anyquery](https://github.com/julien040/anyquery) 🏎️ 🏠 ☁️ - Query more than 40 apps with one binary using SQL. It can also connect to your PostgreSQL, MySQL, or SQLite compatible database. Local-first and private by design.
- [metatool-ai/metatool-app](https://github.com/metatool-ai/metatool-app) 📇 ☁️ 🏠 🍎 🪟 🐧 - MetaMCP is the one unified middleware MCP server that manages your MCP connections with GUI.
- [mindsdb/mindsdb](https://github.com/mindsdb/mindsdb) - Connect and unify data across various platforms and databases with [MindsDB as a single MCP server](https://docs.mindsdb.com/mcp/overview).
- [glenngillen/mcpmcp-server](https://github.com/glenngillen/mcpmcp-server) ☁️ 📇 🍎 🪟 🐧 - A list of MCP servers so you can ask your client which servers you can use to improve your daily workflow.
- [mcpproxy-go](https://github.com/smart-mcp-proxy/mcpproxy-go) - Local MCP proxy that aggregates multiple servers behind a single endpoint. Features BM25 tool discovery, quarantine security, activity logging, Docker isolation, and web UI.
- [wegotdocs/open-mcp](https://github.com/wegotdocs/open-mcp) 📇 🏠 🍎 🪟 🐧 - Turn a web API into an MCP server in 10 seconds and add it to the open source registry: [https://open-mcp.org](https://open-mcp.org)
- [PipedreamHQ/pipedream](https://github.com/PipedreamHQ/pipedream/tree/master/packages/mcp-server) ☁️ 🏠 - Connect with 2,500 APIs with 8,000+ prebuilt tools, and manage servers for your users, in your own app.
- [VeriTeknik/pluggedin-mcp-proxy](https://github.com/VeriTeknik/pluggedin-mcp-proxy) 📇 🏠 - A comprehensive proxy server that combines multiple MCP servers into a single interface with extensive visibility features. It provides discovery and management of tools, prompts, resources, and templates across servers, plus a playground for debugging when building MCP servers.
- [tigranbs/mcgravity](https://github.com/tigranbs/mcgravity) 📇 🏠 - A proxy tool for composing multiple MCP servers into one unified endpoint. Scale your AI tools by load balancing requests across multiple MCP servers, similar to how Nginx works for web servers.
- [MetaMCP](https://github.com/metatool-ai/metatool-app) 📇 ☁️ 🏠 🍎 🪟 🐧 - MetaMCP is the one unified middleware MCP server that manages your MCP connections with GUI.
- [WayStation-ai/mcp](https://github.com/waystation-ai/mcp) ☁️ 🍎 🪟 - Seamlessly and securely connect Claude Desktop and other MCP hosts to your favorite apps (Notion, Slack, Monday, Airtable, etc.). Takes less than 90 secs.
- [sxhxliang/mcp-access-point](https://github.com/sxhxliang/mcp-access-point) 📇 ☁️ 🏠 🍎 🪟 🐧 - Turn a web service into an MCP server in one click without making any code changes.
Consider moving this entry to a 'Databases' section if one exists, or creating one. Database-specific tools don't fit the 'Aggregators' category which is described as 'Servers for accessing many apps and tools through a single MCP server.'

### 📂 Browser Automation
Web content access and automation capabilities. Enables searching, scraping, and processing web content in AI-friendly formats.

- [aircodelabs/grasp](https://github.com/aircodelabs/grasp) 📇 🏠 - Self-hosted browser using agent with built-in MCP and A2A support.
- [Automata-Labs-team/MCP-Server-Playwright](https://github.com/Automata-Labs-team/MCP-Server-Playwright) 🐍 - An MCP server for browser automation using Playwright
- [blackwhite084/playwright-plus-python-mcp](https://github.com/blackwhite084/playwright-plus-python-mcp) 🐍 - An MCP python server using Playwright for browser automation, more suitable for llm
- [browserbase/mcp-server-browserbase](https://github.com/browserbase/mcp-server-browserbase) 🎖️ 📇 - Automate browser interactions in the cloud (e.g. web navigation, data extraction, form filling, and more)
- [browsermcp/mcp](https://github.com/browsermcp/mcp) 📇 🏠 - Automate your local Chrome browser
- [co-browser/browser-use-mcp-server](https://github.com/co-browser/browser-use-mcp-server) 🐍 - browser-use packaged as an MCP server with SSE transport. includes a dockerfile to run chromium in docker + a vnc server.
- [executeautomation/mcp-playwright-server](https://github.com/executeautomation/playwright-mcp-server) 📇 - An MCP server using Playwright for browser automation and webscrapping
- [eyalzh/browser-control-mcp](https://github.com/eyalzh/browser-control-mcp) 📇 🏠 - An MCP server paired with a browser extension that enables LLM clients to control the user's browser (Firefox).
- [getrupt/ashra-mcp](https://github.com/getrupt/ashra-mcp) 🐍 🏠 - Extract structured data from any website. Just prompt and get JSON.
- [kimtth/mcp-aoai-web-browsing](https://github.com/kimtth/mcp-aoai-web-browsing) 🐍 🏠 - A `minimal` server/client MCP implementation using Azure OpenAI and Playwright.
- [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) - Official Microsoft Playwright MCP server, enabling LLMs to interact with web pages through structured accessibility snapshots
- [modelcontextprotocol/server-puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/server-puppeteer) 📇 🏠 - Browser automation for web scraping and interaction
- [ndthanhdev/mcp-browser-kit](https://github.com/ndthanhdev/mcp-browser-kit) 📇 🏠 - An MCP Server for interacting with manifest v2 compatible browsers.

## Build Tools & Dependency Management

### 🔧 Dependency Analysis
Tools for analyzing and managing project dependencies across build systems.

- [arvindand/maven-tools-mcp](https://github.com/arvindand/maven-tools-mcp) ☕ ☁️ 🏠 🍎 🪟 🐧 - Universal Maven Central dependency intelligence for JVM build tools (Maven, Gradle, SBT, Mill). Provides version lookups, dependency health checks, age analysis, release patterns, and upgrade guidance with Context7 integration.

## Monitoring & Observability

### 📊 Metrics & Monitoring
Tools for collecting, querying, and analyzing metrics in DevOps environments.

- [CaesarYangs/prometheus_mcp_server](https://github.com/CaesarYangs/prometheus_mcp_server) 🐍 ☁️ - A Model Context Protocol server enabling LLMs to query, analyze, and interact with Prometheus databases through predefined routes.
- [etruong42/prometheus-mcp](https://github.com/etruong42/prometheus-mcp) 🐍 ☁️ - MCP server to connect LLMs with Prometheus HTTP API for metrics querying and analysis.
- [loginmqv/mcp-server-prometheus](https://github.com/loginmqv/mcp-server-prometheus) 📇 ☁️ - MCP server for interacting with Prometheus, enabling AI assistants to query and analyze metrics data.
- [pab1it0/prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server) 🐍 ☁️ - A Model Context Protocol server that enables AI assistants to query and analyze Prometheus metrics through standardized interfaces.
- [VictoriaMetrics-Community/mcp-victoriametrics](https://github.com/VictoriaMetrics-Community/mcp-victoriametrics) 🏎️ ☁️ - The implementation of Model Context Protocol (MCP) server for VictoriaMetrics. This provides access to your VictoriaMetrics instance and seamless integration with VictoriaMetrics APIs and documentation.

### 🔔 Alerting & Notification
Tools for managing alerts and notifications in monitoring systems.

- [kaznak/alertmanager-mcp](https://github.com/kaznak/alertmanager-mcp) 📇 ☁️ - A Model Context Protocol server that integrates with Prometheus Alertmanager for alert management and notification.

### 🔍 Application Performance Monitoring
Tools for monitoring application performance and infrastructure health.

- [dynatrace-oss/dynatrace-mcp](https://github.com/dynatrace-oss/dynatrace-mcp) 📇 ☁️ - MCP server for Dynatrace Observability monitoring, providing AI-powered insights into application performance and infrastructure health.
- [last9/last9-mcp-server](https://github.com/last9/last9-mcp-server) 🏎️ ☁️ - Last9 MCP Server for observability and monitoring, providing AI assistants with access to metrics, logs, and traces.
- [willibrandon/CursorMCPMonitor](https://github.com/willibrandon/CursorMCPMonitor) #️⃣ 🏠 - Real-time monitoring tool for Model Context Protocol interactions in Cursor AI editor. Track, analyze, and debug AI context exchanges.
- [Polar Signals Remote MCP](https://www.polarsignals.com/blog/posts/2025/07/17/the-mcp-for-performance-engineering) 🐍 ☁️ - MCP server for Polar Signals Cloud continuous profiling platform, enabling AI assistants to analyze CPU performance, memory usage, and identify optimization opportunities in production systems.

## Project & Service Management

### 🎫 Ticketing Systems
Tools for managing customer support tickets and helpdesk operations.

- [effytech/freshdesk-mcp](https://github.com/effytech/freshdesk_mcp) 🐍 ☁️ - MCP server that integrates with Freshdesk, enabling AI models to interact with Freshdesk modules and perform various support operations.
- [dbsanfte/topdesk-mcp](https://github.com/dbsanfte/topdesk-mcp) 🐍 ☁️ - MCP server for the Topdesk ticketing system, allowing AI models to interact with and add comments to incident tickets.

### 📋 Project Management
Tools for managing projects, issues, and workflows.

- [nguyenvanduocit/jira-mcp](https://github.com/nguyenvanduocit/jira-mcp) 🏎️ ☁️ - A Go-based MCP connector for Jira that enables AI assistants like Claude to interact with Atlassian Jira. This tool provides a seamless interface for AI models to perform common Jira operations including issue management, sprint planning, and workflow transitions.
- [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) 🐍 ☁️ - MCP server for Atlassian products (Confluence and Jira). Supports Confluence Cloud, Jira Cloud, and Jira Server/Data Center. Provides comprehensive tools for searching, reading, creating, and managing content across Atlassian workspaces.

## Frameworks

- [MervinPraison/praisonai-mcp](https://github.com/MervinPraison/praisonai-mcp) 🐍 🏠 ☁️ - AI Agents framework with 64+ built-in MCP tools for automation, including search, memory, workflows, code execution, and file operations.
Frameworks for building your own MCP servers.

- [FastMCP](https://github.com/jlowin/fastmcp) 🐍 - A high-level framework for building MCP servers in Python
- [FastMCP](https://github.com/punkpeye/fastmcp) 📇 - A high-level framework for building MCP servers in TypeScript

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
