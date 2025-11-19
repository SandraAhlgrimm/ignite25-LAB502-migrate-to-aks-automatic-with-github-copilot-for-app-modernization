# Workshop Analysis: Microsoft Ignite 2025 LAB502

## Repository Overview

This repository contains **LAB502: Migrate to AKS Automatic with GitHub Copilot for App Modernization**, one of the hands-on workshop labs for Microsoft Ignite 2025.

### Content Owners
- **Diego Casati** ([GitHub: @dcasati](https://github.com/dcasati))
- **Ken Kilty** ([GitHub: @KenKilty](https://github.com/KenKilty))

---

## How Java-Related is This Repository?

**Very Java-focused** - This workshop is fundamentally centered around Java and Spring Boot technologies:

### Primary Technologies
1. **Spring Boot PetClinic Application**
   - The workshop uses the iconic [Spring Boot PetClinic](https://github.com/spring-projects/spring-petclinic) as the modernization target
   - This is a reference Spring Boot application that demonstrates best practices

2. **Java Ecosystem Components**
   - **Build Tool**: Maven (`mvn` commands used throughout)
   - **Java Version**: Java 17 or 21 (Microsoft OpenJDK)
   - **Database**: PostgreSQL with Spring Data JPA
   - **Authentication**: Spring Security with migration to Azure Entra ID

3. **Spring-Specific Features**
   - Spring Boot configuration-driven architecture
   - Spring Cloud Azure dependencies
   - Spring Data PostgreSQL integration
   - Spring Boot auto-configuration for database connections

### Workshop Java Content

The workshop demonstrates:
- Running Spring Boot applications locally with PostgreSQL
- Using **GitHub Copilot App Modernization** to assess Spring Boot applications
- Migrating Spring Boot apps from password-based to managed identity authentication
- Containerizing Spring Boot applications for Kubernetes
- No Java code changes required (configuration-driven migration)
- Adding Spring Cloud Azure BOM and dependencies to `pom.xml`

**Key Advantage**: The workshop highlights that thanks to Spring Boot's configuration-driven approach, the entire migration from password authentication to Azure Managed Identity requires **zero Java code changes** - only configuration file updates.

---

## Microsoft Ignite 2025 Workshop Catalog

The team at Microsoft has created an extensive collection of **56 hands-on labs** for Ignite 2025. Here are the related workshops:

### AI & Agent Development Labs (LAB5XX Series)

#### Agentic AI & Multi-Agent Systems
- **LAB510**: The Power of GitHub Copilot in VS Code
- **LAB511**: Build Agentic Knowledge Bases: Next-Level RAG with Azure AI Search
- **LAB512**: Prototyping Multimodal Agents with Microsoft Foundry and the AI Toolkit
- **LAB513**: Build A2A and MCP Systems Using SWE Agents and Agent Framework
- **LAB514**: Build and Deploy AI Agents with MCP and Azure Functions
- **LAB515**: Build Advanced AI Agents with PostgreSQL
- **LAB516**: Safeguard Your Agents with AI Red Teaming Agent in Microsoft Foundry
- **LAB518**: Multi-Agent Apps with Microsoft Agent Framework or LangGraph
- **LAB519**: Governing AI Apps & Agents with AI Gateway in Azure API Management

#### Cloud & Infrastructure Modernization
- **LAB502**: Migrate to AKS Automatic with GitHub Copilot for App Modernization *(This Repository)*
- **LAB504**: Connect, Secure and Manage Hybrid, Multicloud and Edge with Azure Arc

#### Data & Analytics
- **LAB532**: Get Real with Real-Time Intelligence to Transform Data into Action
- **LAB533**: Build Scalable AI and Data Solutions in SQL Database in Microsoft Fabric
- **LAB534**: Build Real-Time Analytics with Cosmos DB in Microsoft Fabric

#### Security Labs (LAB54X Series)
- **LAB540**: Microsoft Purview Integration with Microsoft Defender XDR
- **LAB541**: Defend Against Threats with Microsoft Defender
- **LAB542**: Zero Trust Lab: Securing Identities and Devices with Intune and Entra
- **LAB543**: Perform Threat Hunting in Microsoft Sentinel
- **LAB545**: Manage Sensitive Data Using Information Protection in the Age of AI
- **LAB546**: Securing the Stack: Zero Trust for Data, Infra, Network and SOC
- **LAB547**: Implement Insider Risk Management and Adaptive Protection for AI
- **LAB548**: Prevent Data Exposure in Copilot and AI Apps with Data Loss Prevention

#### Microsoft 365 & Copilot Agent Development (LAB56X Series)
- **LAB560**: Building Declarative Agents with TypeSpec and M365 Agents Toolkit
- **LAB564**: Architect a Goal-Driven AI Agent with Copilot Studio
- **LAB565**: Makers in Action: Crafting Microsoft 365 Copilot Agents for Real-World
- **LAB570**: Building Agentic Solutions with Copilot Studio
- **LAB571**: Build a Pizza Ordering Agent with Microsoft Foundry and MCP
- **LAB590**: Building Collaborative Agents in Microsoft Teams with Teams AI Library

#### Healthcare & Industry-Specific AI (LAB59X Series)
- **LAB596**: Working with Healthcare AI Models: From Set-Up to Use Case
- **LAB598**: Agentic AI in Healthcare: Multi-Agent Orchestration in Action

---

## Workshop Structure

The LAB502 workshop follows a comprehensive hands-on format:

### Learning Path
1. **Welcome to Your Lab Environment** - Setup and prerequisites
2. **Verify and Explore PetClinic Locally** - Run Spring Boot app with PostgreSQL
3. **Application Modernization** - Use GitHub Copilot to assess the application
4. **Take Action on Findings** - Implement Azure PostgreSQL with Managed Identity
5. **Generate Containerization Assets With AI** - Use AI to create Docker/K8s manifests
6. **Deploy To AKS** - Deploy to Azure Kubernetes Service Automatic
7. **Workshop Recap** - Review accomplishments
8. **Next Steps** - Continue learning resources

### Technologies Demonstrated
- Azure Kubernetes Service (AKS) Automatic
- GitHub Copilot App Modernization
- Azure Database for PostgreSQL Flexible Server
- Azure Workload Identity
- Azure Service Connector
- Containerization Assist MCP Server
- Spring Boot PetClinic

---

## Key Workshop Outcomes

By completing this workshop, participants learn to:
- ✅ Assess Spring Boot applications for cloud readiness using AI
- ✅ Migrate from self-hosted PostgreSQL to Azure Database for PostgreSQL
- ✅ Implement passwordless authentication with Azure Workload Identity
- ✅ Generate production-ready Docker and Kubernetes manifests using AI
- ✅ Deploy to AKS Automatic with enterprise-grade security

### Modern Cloud-Native Patterns
The workshop demonstrates the complete journey from:
- **Before**: Local Spring Boot app with password-based PostgreSQL authentication
- **After**: Cloud-native app on AKS Automatic with Entra ID managed identity authentication

---

## Additional Resources

### Official Links
- **Ignite Next Steps**: https://aka.ms/Ignite25-Next-Steps
- **AKS Community Calls**: https://blog.aks.azure.com/webinars/
- **AKS Labs**: https://azure-samples.github.io/aks-labs/
- **AKS Automatic Docs**: https://learn.microsoft.com/azure/aks/intro-aks-automatic
- **Azure Global Black Belt Blogs**: https://azureglobalblackbelts.com/

### Documentation Format
The workshop content is delivered via:
- **MkDocs-based documentation** with Material theme
- **Interactive hands-on labs** with step-by-step instructions
- **Screenshot guidance** for visual learners
- **Troubleshooting guide** for common issues
- **Microsoft Learn MCP Server** integration for up-to-date documentation

---

## Repository Statistics

- **Primary Language**: Markdown/Documentation (no Java source code in this repo - it references external PetClinic)
- **Structure**: MkDocs-based documentation site
- **License**: MIT with separate docs license
- **Microsoft Learn MCP Server**: Integrated for AI-powered documentation access

---

## Conclusion

This repository represents one component of Microsoft's comprehensive Ignite 2025 learning initiative. The team has created **56 hands-on workshop labs** covering AI agents, cloud infrastructure, security, data analytics, and industry-specific solutions. 

**LAB502 is highly Java-centric**, focusing specifically on modernizing Spring Boot applications for Azure Kubernetes Service using AI-powered tools. It demonstrates practical, real-world migration patterns that Java developers can apply to their own applications.
