# Transfer Large Files with External Services and MCP

## ⚙️ Setup for the transfer of large binary files to S3
- Download the S3 Open API Specification (OAS) and save it localy
- Activate the Salesforce MCP Server (Headless 360 MCP Server) if you want to use AIforce
- Create an External Client App to connect to your AI assistant of choice
- Create a Named Credential for S3 in your Salesforce Org
- Register an External Service for your S3 bucket and upload the S3 OAS you previously downloaded. You can register an External Service using AIforce via the Salesforce MCP Server (Headless 360 MCP Server) or via the UI
- Use your favourite AI assistant to write APEX that calls the External Service and uploads the File into S3 by passing the Content document reference
- Update the Opportunity Trigger so it calls the class you created once an Opportunity is Closed-won

## 👩‍🎓 Trailhead
- [Get started with External Services](https://trailhead.salesforce.com/content/learn/modules/external-services/get-started-with-external-services)
  
## :books: Official Documentation
- [Do More with External Services Binary File Improvements](https://help.salesforce.com/s/articleView?id=release-notes.rn_ext_services_enhancements.htm&release=262&type=5)
- [AIforce](https://help.salesforce.com/s/articleView?id=platform.aif_welcome.htm&type=5)
- [Headless 360 MCP Server (Beta)](https://developer.salesforce.com/docs/platform/hosted-mcp-servers/references/reference/headless-360-mcp.html)
