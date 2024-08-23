# Preparing for Your Organization's AI Workloads

This repo is intended as a template for Microsoft AI Tour repositories

## Session Desciption

Any new application can introduce risk to your organisation, so how do you keep AI applications controlled and compliant? This session explores governance and compliance controls for Azure AI services, including the fundamentals of Identity and cost management. Follows the Governing AI report and NIST AI Risk Management Framework.

![image](https://github.com/user-attachments/assets/01951241-93d2-4fe3-8672-f6f3c00a4f6d)


## Technology Used
- Azure Compute
- Microsoft Entra
- Azure OpenAI
- Azure Security Products – Microsoft Purview, Microsoft Defender for AI


## Content Owners

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<table>
<tr>
    <td align="center"><a href="http://learnanalytics.microsoft.com">
        <img src="https://github.com/Orin-Thomas.png" width="100px;" alt="Orin Thomas"/><br />
        <sub><b>Orin Thomas
</b></sub></a><br />
            <a href="https://github.com/Orin-Thomas" title="talk">📢</a> 
    </td>
</tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->


## Responsible AI
Microsoft is committed to helping our customers use our AI products responsibly, sharing our learnings, and building trust-based partnerships through tools like Transparency Notes and Impact Assessments. Many of these resources can be found at https://aka.ms/RAI. Microsoft’s approach to responsible AI is grounded in our AI principles of fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability.

Large-scale natural language, image, and speech models - like the ones used in this sample - can potentially behave in ways that are unfair, unreliable, or offensive, in turn causing harms. Please consult the Azure OpenAI service Transparency note to be informed about risks and limitations. The recommended approach to mitigating these risks is to include a safety system in your architecture that can detect and prevent harmful behavior. Azure AI Content Safety provides an independent layer of protection, able to detect harmful user-generated and AI-generated content in applications and services. Azure AI Content Safety includes text and image APIs that allow you to detect material that is harmful. We also have an interactive Content Safety Studio that allows you to view, explore and try out sample code for detecting harmful content across different modalities. The following quickstart documentation guides you through making requests to the service.

Another aspect to take into account is the overall application performance. With multi-modal and multi-models applications, we consider performance to mean that the system performs as you and your users expect, including not generating harmful outputs. It's important to assess the performance of your overall application using generation quality and risk and safety metrics.

You can evaluate your AI application in your development environment using the prompt flow SDK. Given either a test dataset or a target, your generative AI application generations are quantitatively measured with built-in evaluators or custom evaluators of your choice. To get started with the prompt flow sdk to evaluate your system, you can follow the quickstart guide. Once you execute an evaluation run, you can visualize the results in Azure AI Studio. Empowering responsible AI practices | Microsoft AI Explore how Microsoft is committed to advancing AI in a way that is driven by ethical principles that put people first.
