# Argo Secure | Copilot for Security
**Author: Jerald Dawkins** <br> **Publisher: CISO Global**

## Integration Prerequisites
- API Key for your ArgoSecure instance
- Access to the ArgoSecure Global Assets module

## Skills & Prompts
Below are a set of prompts you can use in Copilot for Security to invoke the API operations leveraged by the plugin.
|      API Endpoint                | Request Type |                         Prompt                                                                                                                                                                                      |
| -------------------------------- | ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `/api/globalassets/{tenantId}`   |      GET     | `Use ArgoSecure to get a list of all assets and endpoints for my tenant ID, {tenant_id}. Tell me if {endpoint_name} is currently protected by Security Monitoring, Backup Management, and Vulnerability Scanning. ` |
| `/api/globalassetdetails`        |      POST    | `Use ArgoSecure to get asset details and the top 10 vulnerabilities for endpoint name: {endpoint_name}. My tenant ID is {tenant_id} and my applicationIds string is: ["833","832"]`                                 |



