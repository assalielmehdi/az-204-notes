# Identify the technology options

In this unit, we'll explore the Azure technology options that are available to automate and integrate your business processes.

## Common business issues

In business, one way to guarantee high-quality products and service to customers is to design and implement strict business processes.

Business processes modeled in software are often called workflows. Azure includes four different technologies that you can use to build and implement workflows that integrate multiple systems:

- Logic Apps
- Microsoft Power Automate
- WebJobs
- Azure Functions

## Design-first technologies

When business analysts discuss and plan a business process, they may draw a flow diagram on paper. We call this approach a design-first approach.

With __Logic Apps__ and __Microsoft Power Automate__, you can take a similar approach to designing a workflow.


|                                  | Microsoft Power Automate                                    | Logic Apps                                                                                |
|----------------------------------|-------------------------------------------------------------|-------------------------------------------------------------------------------------------|
| Intended users                   | Office workers and business analysts                        | Developers and IT pros                                                                    |
| Intended scenarios               | Self-service workflow creation                              | Advanced integration projects                                                             |
| Design tools                     | GUI only. Browser and mobile app                            | Browser and Visual Studio designer. Code editing is possible                              |
| Application Lifecycle Management | Power Automate includes testing and production environments | Logic Apps source code can be included in Azure DevOps and source code management systems |

## Code-first technologies

The developers on your team will likely prefer to write code when they want to orchestrate and integrate different business applications into a single workflow. We call this approach a code-first approach.

With __WebJobs__ and __Functions__, you can take a similar approach to coding a workflow.

|                                           | Azure WebJobs                          | Azure Functions                             |
|-------------------------------------------|----------------------------------------|---------------------------------------------|
| Supported languages                       | C# if you are using the WebJobs SDK    | C#, Java, JavaScript, PowerShell, and so on |
| Automatic scaling                         | No                                     | Yes                                         |
| Development and testing in a browser      | No                                     | Yes                                         |
| Pay-per-use pricing                       | No                                     | Yes                                         |
| Integration with Logic Apps               | No                                     | Yes                                         |
| Package managers                          | NuGet if you are using the WebJobs SDK | Nuget and NPM                               |
| Can be part of an App Service application | Yes                                    | Yes (hosted under App Service plan)         |
