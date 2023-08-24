---
id: kanbanize
title: Kanbanize Integration
sidebar_label: Kanbanize
description: A step-by-step guide on seamlessly integrating Conviso Platform with Kanbanize for efficient vulnerability management and issue control.
keywords:  [Kanbanize Integration]
---

<div style={{textAlign: 'center'}}>

[![img](../../static/img/kanbanize.png  "Image for Kanbanize, Defect Tracking tool, with Conviso Platform")](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)

</div>

## Introduction
The  [Conviso Platform](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826) integrates with [Kanbanize](https://kanbanize.com/pt) enabling the creation of issues, comments, and a Webhook for issue comments.

### Integration Capabilities
This integration enhances issue control management and vulnerability consolidation between systems. It facilitates seamless interaction and communication between various aspects of the Vulnerability Management process. The integration offers the following capabilities:

**From Kanbanize to Conviso Platform:**
* Automatically display comments added by users in Kanbanize's discussion field on the vulnerability's Security Experts tab.
* Foster interaction by sharing information from Kanbanize with the development team responsible for corrections in Vulnerability Management from Conviso Platform.

**From Conviso Platform to Kanbanize:**
* Generates new issues in Kanbanize based on events within Conviso Platform's Vulnerability Management System, such as identified vulnerabilities or completed security assessments.
* Establishes a linkage between vulnerabilities detected in Conviso Platform and their relevant issues in Kanbanize, enhancing traceability and collaborative efforts.
* Updates Kanbanize issues when specific actions occur in Conviso Platform's Vulnerability Management System, such as changes in vulnerability status, assessment completions, or updates to risk levels.
* Automatically generates rework tasks in Kanbanize for vulnerabilities that require further attention or corrections after the initial assessment in Conviso Platform.
* Transitions Kanbanize issues to appropriate workflow stages when vulnerabilities are resolved or mitigated within Conviso Platform's Vulnerability Management System.

### Prerequirements
To set up the integration, you'll need the following information:

1. Kanbanize's website address;

2. Email or Username associated with Kanbanize;

3. API Token for authentication purposes. See **[here how to get Conviso API Key](../api/generate-apikey.md)** and **[here to get the API Token from Kanbanize](https://kanbanize.com/api)**.

## Usage
To seamlessly integrate Conviso Platform with Kanbanize, follow these step-by-step procedures:

**[1 - Configure the initial integration setup between Conviso Platform and  Kanbanize](#configure-the-initial-integration-setup-between-conviso-platform-and-kanbanize)**

## Configure the initial integration setup between Conviso Platform and Kanbanize

Follow the instructions below to complete the integration setup.

**Step 1 -** First, access **Kanbanize** and copy the **URL** of your site, as shown in the image below: 

<div style={{textAlign: 'center'}}>

[![img](../../static/img/kanbanize-img1.png "A clipping of a Kanbanize platform screen.")](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)
</div>

**Step 2 -** Next, to generate the **API Token **(label), visit the following [link](https://kanbanize.com/api). After clicking the Create API token button, as shown in the image above, copy the API key.

<div style={{textAlign: 'center'}}>

[![img](../../static/img/kanbanize-img2.png "A clipping of API session from Kanbanize platform screen.")](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)
</div>

**Step 3** - Now that you have the required information, go to **Conviso Platform**, look for the **Integrations (1)** on the left side menu, choose **Defect Tracker (2)** at the Categories panel to the right and finally click the **Integrate (3)** button just below Kanbanize’s card, as illustrated in the example image below: 

[![img](../../static/img/kanbanize-img3.png "A screenshot of a Conviso Platform screen for integration with Kanbanize.")](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)
</div>

**Step 5** - Then, enter all **Kanbanize** information in the fields requested by Conviso Platform, which were demonstrated how to obtain at the beginning of this document. 
[![img](../../static/img/kanbanize-img4.png "A screenshot of a Conviso Platform screen for integration with Kanbanize.")](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)
</div>

**Note:** The Verify SSL checkbox must be checked only if the certificate associated with Kanbanize is issued by a Public Certificate Authority. For Private CAs or self-signed certificates, use https:// at the site address URL and leave this box unchecked. 

**Step 6 - Severity Mapping** refers to Kanbanize's two-way integration with Conviso Platform. Select which severity will be referenced to Kanbanize's priority:

[![img](../../static/img/kanbanize-img5.png "A screenshot of a Conviso Platform screen for integration with Kanbanize.")](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)
</div>

**Step 7 -** Then, in **Configuration**, click on the **Add** button to start pairing Conviso Platform Projects with **Kanbanize Projects:**

[![img](../../static/img/kanbanize-img6.png "A screenshot of a Conviso Platform screen for integration with Kanbanize.")](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)
</div>


**Step 8 -** At the drop-down list **New Project Documentation**, select the **Conviso Platform Project** you want to associate to your **Kanbanize Project**, which will be chosen at the drop-down list Kanbanize Project. You can also perform **Issue** and **status configuration**.

[![img](../../static/img/kanbanize-img7.png "A screenshot of a Conviso Platform screen for integration with Kanbanize.")](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)
</div>

**Step 9 -** After mapping all Conviso Platform statuses to Kanbanize statuses, click on the **Save button**.

**Step 10 -** Click on the **Check Integration Connection** button to check if the platform connects with Kanbanize server, if everything is ok you will see the following message:
[![img](../../static/img/kanbanize-img8.png "A screenshot of a Conviso Platform screen for integration with Kanbanize.")](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)
</div>

**Step 11** - After saving your integration configuration, you may want to review, modify or delete it from Conviso Platform. To do so, at your integration configuration panel, choose the Edit icon to review or change it; If you want to completely delete it, use the Trash icon at its right: 

[![img](../../static/img/kanbanize-img9.png "A screenshot of a Conviso Platform screen for integration with Kanbanize.")](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)
</div>


**Step 12** - Whenever a new vulnerability is detected, it is automatically sent to the project in Kanbanize, as shown in the image below:

[![img](../../static/img/kanbanize-img10.png "A clipping of a Kanbanize platform screen in the backlog.")](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)
</div>

## Support

Should you have any questions or require assistance while using the Conviso Platform, feel free to contact our dedicated support team.

## Resources
By exploring our content, you'll find resources that will enhance your understanding of the importance of a Security Application Program.

[Conviso Blog](https://bit.ly/3JtXM8A): Explore our blog, which offers a collection of articles and posts covering a wide range of AppSec topics. The content on the blog is primarily in English.

[Conviso's YouTube Channel](https://bit.ly/3NIbbfM): Access a wealth of informative videos covering various topics related to AppSec. Please note that the content is primarily in Portuguese.

[AppSec to Go - Conviso's Podcast on AppSec](https://spoti.fi/43UJQwN): Tune in to our podcast, where we discuss AppSec-related subjects, providing valuable insights and discussions. The podcast is conducted in Portuguese.

[![Discover Conviso Platform, a solution for ASPM!](https://no-cache.hubspot.com/cta/default/5613826/interactive-125788977029.png)](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)