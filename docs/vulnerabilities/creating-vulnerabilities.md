---
id: creating-vulnerabilities
title: How to create a vulnerability
sidebar_label: Creating Vulnerabilities
description: Learn how to create a vulnerability on the Conviso Platform, using ready-made templates or entering details manually.
keywords: [vulnerability management]
---

## Introduction

When creating a vulnerability in the Conviso Platform, we associate it with an asset within the project scope.

## Usage

There are two methods available for creating a vulnerability:

**[1 - Add vulnerabilities on the Conviso Platform](#adding-vulnerabilities)**

**[2 - Import vulnerabilities from other tools](#importing-vulnerabilities)**

## Adding vulnerabilities
In the "Vulnerabilities" page, you can add vulnerabilities using the "**+ New Vulnerability**" button:

[![img](../../static/img/creating-vuln-img1.png 'Vulnerability management on the Conviso Platform.')](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)

**Just follow these steps:**

**Step 1 -** Choose between using one of our Vulnerability templates or creating a new project entirely from scratch. If you select "**Insert details manually**", click "**Next**".

[![img](../../static/img/creating-vuln-img2.png 'Vulnerability model selection interface or creation manual on the Conviso Platform.')](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)

If you choose a template, make your selection, and then click "**Next**."  [Learn more about the Vulnerabilities Template.](XX)

**Step 2 - To create your vulnerability, please ensure that you fill in all the required fields on the form:**

[![img](../../static/img/creating-vuln-img3.png 'Field filling interface to create a vulnerability.')](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)

**Title:** A label describing the vulnerability (mandatory);

**Description:** For you to provide as much information as possible about the vulnerability.

**Solution:** Description of how to fix the vulnerability; use references such as OWASP to base your answer (mandatory).

**Categories:** Select which CWE this vulnerability belongs to (optional);

**Patterns:** Select which currently used patterns (OWASP) this vulnerability belongs to (optional);

**Reference:** Place the sources where the information regarding this vulnerability was taken (mandatory);

**Note:** If you select a template, the form will be auto-populated.

Click "**Next**" after completing all the necessary fields.

**Step 3 - Select the Failure Type that best describes the issue.**

In this step, you must select the appropriate "Failure Type" that best characterizes the vulnerability you're creating. 

[![img](../../static/img/creating-vuln-img4.png 'Failure Type available on the Conviso Platform.')](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)

The available Failure Types include:

### Web Failure Type

**Web** denotes vulnerabilities occurring at the web application layer. Attackers can exploit these vulnerabilities within the code or configuration of web servers, browsers, or related components. Examples of web failures include SQL injection, cross-site scripting, and cross-site request forgery.

[![img](../../static/img/creating-vuln-img5.png 'Selection of the failure type to classify a web vulnerability.')](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)

**Request:**  Refers to the client's request, typically sent from a web browser to a web server.

**Response:** Is the response sent by the web server after receiving the request from the client.

**Method:** This field allows you to choose the HTTP method for your request, such as GET, POST, PUT, DELETE, etc. Different methods have different implications and can affect the behavior of your request. \


**Scheme:** The scheme field lets you choose whether to use the HTTP, HTTPS, or WSS protocol for your request.

**URL:** This field requires the URL of the application. Different methods identify the vulnerability, have different implications, and can affect the behavior of your request.

**Port:** The port number specifies the endpoint on the server that listens for the request. By default, HTTP uses port 80, and HTTPS uses port 443. If your target server uses a different port, you can specify it here.

**Parameters:** This field is used to capture any input parameters that are involved in the vulnerability.

### Source code Failure Type

**Source Code** category deals with vulnerabilities that occur at the source code level. Attackers can exploit these vulnerabilities within the application's code or logic. Examples include buffer overflow.

[![img](../../static/img/creating-vuln-img6.png 'Selection of the failure type to classify a source code vulnerability.')](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)

**Vulnerable Code:** Insert the code with the vulnerability.

**File:** Indicate the file associated with the vulnerable code snippet.
 
**First line:** Specify the line number that indicates where the code snippet starts.
 
**Vulnerable line:** Specify the line numbers within the file where the vulnerable code is located.

**Source:** Describe the origin or cause of the vulnerability. For example, identify the input or data source that is exploited.

**Sink:** Specify the destination or point in the code where the vulnerability can be exploited.

### Network code Failure Type

**Network** addresses vulnerabilities at the network layer. Attackers can exploit network vulnerabilities involving protocols, IP addresses, ports, or network attack vectors. Examples of network failures include denial of service, man-in-the-middle attacks, and port scanning.

[![img](../../static/img/creating-vuln-img7.png 'Selection of the failure type to classify a network vulnerability.')](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)

**Protocol:** Choose the network protocol used for the vulnerability. Examples include HTTP, HTTPS, FTP, SSH, etc.

**Step 4 - Additional Information and Details:**

This step allows you to provide more information about the vulnerability you're creating:

[![img](../../static/img/creating-vuln-img8.png 'Additional Information about the vulnerability.')](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)

**Impact:** The impact field is one of the most important. Through this, it will be possible to prioritize corrections.
The logic used in this field is the [OWASP Risk Rating methodology](https://owasp.org/www-community/OWASP_Risk_Rating_Methodology) to reach a final result, in which criticality results from probability times impact.

**Probability:** Assess the likelihood of an attacker exploiting the vulnerability. This depends on various factors: exposure, attack complexity, countermeasures, and attacker motivation.

**Link vulnerability to an asset:** Select the asset this vulnerability will impact.

**Link vulnerability to a project:** Select the AppSec project corresponding to the vulnerability.

**Summary overview:** A concise overview of the vulnerability, outlining its context and significance.
 
**Impact:** Provide more details about the impact of the vulnerability.

**Steps to reproduce:** The field of steps for reproduction must always be objective. Present the steps logically, using numbered instructions (e.g., 1, 2, 3).  Use terminology that is universally understood, avoiding jargon or overly technical language. If necessary, provide explanations or context for technical terms. If specific tools are required for reproduction, clearly mention them.

Remember that the goal is to make it as easy as possible for developers to replicate the vulnerability accurately.

Check the box at the bottom of the page **if this vulnerability compromising the asset**.

Once all fields are filled in, click "**Finish**" to register the vulnerability, and it will be marked as "**Created**".

[![img](../../static/img/creating-vuln-img9.png 'Vulnerability registered on the Conviso Platform with the status highlighted.')](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)

## Importing vulnerabilities

The [Conviso CLI](/docs/cli/installation.md) allows you to import vulnerabilities from a SARIF file, such as Trivy or Semgrep, to a project on your Conviso Platform account. [Check out this documentation to learn more](/docs/cli/findings.md).

Additionally, you can explore options for importing scanner results via our integrations, as detailed in our [integrations documentation](/docs/integrations/integrations_intro.md/#consolidate-vulnerability-management-through-integrated-security-scans).  

## Support

If you have any questions or need help using our product, please don't hesitate to contact our support team.

## Resources

By exploring our content, you'll find resources to help you understand vulnerability management:

[How Vulnerability Management Works in Conviso Platform:](https://bit.ly/3LBxR0m) Discover the platform's key features and how it helps detect, prioritize, and remediate vulnerabilities.

[Prioritization of Vulnerabilities:](https://bit.ly/3LBxR0m) Learn best practices for prioritizing vulnerabilities and creating a strategy that works for your organization.

[Vulnerability Management Process:](https://bit.ly/3LgMDIn) Get an overview of the process and learn how to implement it in your organization.

[![Discover Conviso Platform, a solution for ASPM!](https://no-cache.hubspot.com/cta/default/5613826/interactive-125788977029.png)](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)