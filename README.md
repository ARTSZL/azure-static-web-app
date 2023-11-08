# Simple Static Website Deploy with Azure Static Web Apps

This project demonstrates how to create a basic static website and deploy it to Azure using Azure Static Web Apps. Azure Static Web Apps is a hosting service that allows you to easily deploy and manage static web applications.

## Prerequisites

Before you begin, make sure you have the following prerequisites:

- **Azure Account:** You'll need an Azure account to create and manage the Azure Static Web App. If you don't have one, you can sign up for an [Azure account](https://azure.com).

- **Azure CLI:** Install the [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli) on your local machine. You'll use this command-line tool to interact with Azure services.

- **Website Content:** Create your static website using HTML, CSS, and JavaScript. You can use any code editor of your choice to build your website.

## Getting Started

Follow these steps to create and deploy your static website to Azure:

1. Create your static website with HTML, CSS, and JavaScript content.

2. Run to login to Azure

    `az login`
   in your terminal and follow the prompts to sign in to your Azure account.

3. Run the following command to create a new Azure Static Web App resource:

   ```bash
   az staticwebapp create --name azure-static-web-app --location East US --resource-group RG-static-web-app --src "/src" --token "https://github.com/ARTSZL/azure-static-web-app.git"

4. Configure Your Deployment:

- You can configure additional settings for your deployment in the Azure portal. This includes setting up custom domains, enabling authentication, and defining routing rules.

5. Deploy Your Website:

- Once configured, your website will be deployed automatically. You can access it via the provided Azure Static Web Apps URL.

6. Monitor and Manage:

- You can monitor your website's performance and make changes using the Azure portal.

## Customization

Feel free to customize your static website and its content as needed. You can also explore more advanced features offered by Azure Static Web Apps, such as serverless functions, authentication, and more.

## Resources

- [Azure Static Web Apps Documentation](https://learn.microsoft.com/en-us/azure/static-web-apps/)
- [Azure CLI Documentation](https://learn.microsoft.com/en-us/cli/azure/)

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/ARTSZL/azure-static-web-app/blob/main/LICENSE) file for details.
