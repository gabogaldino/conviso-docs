---
id: datastudio
title: Google Looker Studio
sidebar_label: Google Looker Studio
---

# Introduction
[Google Looker Studio](https://datastudio.google.com/) is a powerful business intelligence tool that allows users to generate customized reports and extract data for analysis on BI platforms. This document provides instructions on integrating the Conviso Platform with Google Looker Studio.

## Usage

Access the **Integrations (1)** menu in the Conviso Platform. Navigate to the **Business Intelligence (2)** section in the right panel. Click on the "**Integrate**" **(3)** button.

<div style={{textAlign: 'center'}}>

![img](../../static/img/datastudio-img1.png)

</div>

There are four types of endpoints available to generate a JSON file and feed the BI tool:

* **Deploys:** Returns a JSON with all company deployments.
* **Projects:** Returns all projects linked to the user's scope.
* **Assets:**  Returns all company assets.
* **Users:** Returns a JSON with all company users.


<div style={{textAlign: 'center'}}>

![img](../../static/img/datastudio-img2.png)

</div>

To create a connector with your BI tool, you will need the following information:
* **Conviso Platform URL:** Use the URL ```https://app.convisoappsec.com/```.
* **Endpoint:** Select one of the four available endpoints mentioned above.
* **x-API-key:** Generate your API Key by following the instructions provided [here](../api/generate-apikey.md).

## Google Looker Studio Setup

To set up Conviso Platform integration with Google Data Studio, follow these steps:

**Step 1 -** Log in to your Google Data Studio account. Click on the **"Create" (1)** button and select "**Report"(2)** from the menu:

<div style={{textAlign: 'center'}}>

![img](../../static/img/datastudio-img3.png)

</div>


**Step 2 -** In the search box, **search for ```JSON/CSV/XML```(1)** and choose the "**JSON/CSV/XML Connector" (2):**

<div style={{textAlign: 'center'}}>

![img](../../static/img/datastudio-img4.png)

</div>


**Step 3 -** Click on the "**Authorize**" button to grant Data Studio access to your Google user account:

<div style={{textAlign: 'center'}}>

![img](../../static/img/datastudio-img5.png)

</div>


**Step 4 -** Select your **user account** or provide an existing user's credentials in the floating window that appears and click on the "**Allow**" button to grant access to the connector.

<div style={{textAlign: 'center'}}>

![img](../../static/img/datastudio-img6.png)

</div>


**Step 5 -** Click on the "**Authorize**" button below the ```JSON/CSV/XML``` authorization box.

<div style={{textAlign: 'center'}}>

![img](../../static/img/datastudio-img7.png)

</div>


**Step 6 -** Finally, click on the **close icon to close the Supermetrics floating** window. The following window will be displayed. Fill in the form with the following data:

<div style={{textAlign: 'center'}}>

![img](../../static/img/datastudio-img8.png)

</div>

* **Data Type (1):** Select ```JSON```.
* **Source URL or Google Drive path (2):** Insert ```https://app.convisoappsec.com/api/v2/projects```
* **HTTP headers (3):** Enter "x-api-key:< your-generated-api-key >”. [Check here](../api/generate-apikey.md) to find out how to find it.

Once you have filled in the form, click on the "**Add**" button in the lower right corner. A confirmation window will appear. Click on the **"Add to Report**" button to save the configuration.

<div style={{textAlign: 'center'}}>

![img](../../static/img/datastudio-img9.png)

</div>


Your automatically generated dashboard will be displayed. You can also create your own custom dashboards!

## Support

If you have any questions or need help using our product, please don't hesitate to contact our [support team](http://XX). 

Resources

By exploring our content, you'll find resources to help you understand the importance of security applications data:

[The importance of a platform for managing an AppSec program:](https://bit.ly/42JEfrq) We invite you to learn why an AppSec management platform is essential for companies that want to keep their applications safe and secure.