---
id: viewing-application-results
title: Viewing Application Results
sidebar_label: Viewing Application Results
description:  Conviso Platform has a complete workflow for vulnerability management, such as the process cycle to evaluate, remediate, and mitigate application security weaknesses.
keywords:  [vulnerability management]
---

## Introduction
Conviso Platform has a complete workflow for vulnerability management, such as the process cycle to evaluate, remediate, and mitigate application security weaknesses.

## Usage
Click the "**Vulnerabilities**" option in the left-hand menu to view all identified vulnerabilities.


[![img](../../static/img/view-app-result-img1.png 'Vulnerability management on the Conviso Platform.')](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)

When viewing the list of identified vulnerabilities, you can quickly access a summary of each vulnerability:

**Title:** Title of the Vulnerability.

**Severities:** Severity Level(s) Assigned to the Vulnerability.

**Asset:** Affected Asset or System.

**Type: **Source type of vulnerability, for example, SAST, SCA, AST, and DAST.

There is also a place with the status cluster for you to stay tuned:

[![img](../../static/img/view-app-result-img2.png 'Vulnerability management on the Conviso Platform.')](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)

**Needs Attention**: a summary of pending vulnerabilities that require user attention.

The vulnerabilities will be organized and displayed according to their respective statuses, which can be categorized as follows:

[![img](../../static/img/view-app-result-img3.png 'Vulnerability management on the Conviso Platform.')](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)

**False Positive:** Indicates that the vulnerability is a false positive.

[![img](../../static/img/view-app-result-img4.png 'Vulnerability management on the Conviso Platform.')](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)

**Risk Accepted:** indicates that the vulnerability has been accepted as an acceptable risk, and no action will be taken to fix it.

[![img](../../static/img/view-app-result-img5.png 'Vulnerability management on the Conviso Platform.')](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)

**Fixed:** indicates that the solution to the vulnerability has been accepted.

On this page, there is a **Filter** for you to be able to view vulnerabilities by a specific status, severity, failure type, date, project, or asset:

[![img](../../static/img/view-app-result-img6.png 'Vulnerability management on the Conviso Platform.')](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)

Now, you can manage the vulnerability as a developer!

## Decision Workflow for Vulnerability Management

If a vulnerability has been identified and understood to be neither a false positive nor an accepted risk, it is necessary that this vulnerability becomes part of the workflow of our development squads so that it can be corrected:

[![img](../../static/img/view-app-result-img7.png 'Decision Workflow for Vulnerability Management.')](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)

**Note:** This flow of vulnerabilities can be changed according to [vulnerability policy definitions](/docs/vulnerabilities/integration-policies.md).

Once the vulnerability has been corrected, the process ends and in our [Defect Tracker](/docs/vulnerabilities/defect-tracker-integration.md) tool the card associated with this vulnerability is placed as "**Fixed**", indicating that the cycle has been completed.

## Deduplication of vulnerabilities
Duplicate vulnerabilities from different tools can make vulnerability management hard. They clutter your workflow and mislead your prioritization. 

Conviso Platform solves this problem by merging duplicate vulnerabilities into one entry.

**How It Works**
Conviso Platform automatically merges duplicate vulnerabilities reported by different tools. This helps you:
* Reduce noise and focus on critical issues.
* Prioritize and fix vulnerabilities based on their real impact and severity.
* Improve your workflow and resolve issues faster.

## Support
If you have any questions or require assistance using the Conviso Platform, contact our dedicated support team.

## Resources
By exploring our content, you'll find resources to help you understand vulnerability management:

[How Vulnerability Management Works in Conviso Platform:](https://bit.ly/3LBxR0m) Discover the platform's key features and how it helps detect, prioritize, and remediate vulnerabilities.

[Prioritization of Vulnerabilities:](https://bit.ly/3LBxR0m) Learn best practices for prioritizing vulnerabilities and creating a strategy that works for your organization.

[Vulnerability Management Process:](https://bit.ly/3LgMDIn) Get an overview of the process and learn how to implement it in your organization.

[![Discover Conviso Platform, a solution for ASPM!](https://no-cache.hubspot.com/cta/default/5613826/interactive-125788977029.png)](https://cta-service-cms2.hubspot.com/web-interactives/public/v1/track/redirect?encryptedPayload=AVxigLKtcWzoFbzpyImNNQsXC9S54LjJuklwM39zNd7hvSoR%2FVTX%2FXjNdqdcIIDaZwGiNwYii5hXwRR06puch8xINMyL3EXxTMuSG8Le9if9juV3u%2F%2BX%2FCKsCZN1tLpW39gGnNpiLedq%2BrrfmYxgh8G%2BTcRBEWaKasQ%3D&webInteractiveContentId=125788977029&portalId=5613826)