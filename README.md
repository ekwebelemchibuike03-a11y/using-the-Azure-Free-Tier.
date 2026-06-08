# using-the-Azure-Free-Tier.
Heads on knowledge on opening up an Azure account as a cloud engineer.
# Azure Free Tier Account Setup and Portal Exploration

## Project Overview

This project demonstrates the creation and configuration of a Microsoft Azure Free Tier account. It covers account registration, portal navigation, billing management, security configuration, and deployment of a sample Azure resource.

---

# Objectives

* Create an Azure Free Tier account
* Complete identity verification
* Explore Azure Portal features
* Configure billing and budget alerts
* Understand Microsoft Entra ID security features
* Deploy a test Azure resource
* Document free-tier limitations and best practices

---

# 1. Account Creation

## Step 1: Sign Up for Azure

1. Visit the Azure website.
2. Select **Start Free**.
3. Sign in with a Microsoft account or create a new one.
4. Provide personal information.

### Screenshot 1

*Azure Free Account Registration Page*

## Step 2: Email Verification

1. Enter your email address.
2. Verify using the code sent to your inbox.

### Screenshot 2

*Email Verification Process*

## Step 3: Phone Verification

1. Enter a valid mobile phone number.
2. Receive and enter the SMS verification code.

### Screenshot 3

*Phone Verification Screen*

## Step 4: Payment Verification

1. Add a valid debit or credit card.
2. Azure uses the card only for identity verification.
3. Charges will not occur unless services exceed free limits.

### Screenshot 4

*Payment Method Verification*

---

# 2. Azure Free Tier Benefits

## Included Benefits

| Benefit           | Details                           |
| ----------------- | --------------------------------- |
| Azure Credit      | $200 credit for first 30 days     |
| Popular Services  | Free for 12 months                |
| Selected Services | Always free                       |
| Cost Monitoring   | Available through Cost Management |

## Important Notes

* $200 credit expires after 30 days.
* 12-month services remain free only within usage limits.
* Exceeding limits may incur charges.
* Resources should be monitored regularly.

---

# 3. Azure Portal Navigation

After registration, access the Azure Portal.

## Key Areas

### Home Dashboard

Provides an overview of resources and services.

### Search Bar

Used to locate resources, services, and documentation quickly.

### Resource Menu

Contains:

* Virtual Machines
* Storage Accounts
* Networking
* Databases
* Cost Management
* Microsoft Entra ID

### Screenshot 5

*Azure Portal Home Dashboard*

---

# 4. Dashboard Customization

Azure dashboards can be customized.

## Steps

1. Open Dashboard.
2. Select Edit.
3. Add tiles for frequently used services.
4. Save the dashboard.

Benefits:

* Faster navigation
* Personalized workspace
* Improved monitoring

### Screenshot 6

*Customized Dashboard*

---

# 5. Subscription and Resource Group

## Locate Subscription

1. Search for "Subscriptions".
2. Select the active subscription.

### Screenshot 7

*Azure Subscription Overview*

## Create Resource Group

1. Open Resource Groups.
2. Select Create.
3. Enter:

* Resource Group Name: RG-Learning-Lab
* Region: Closest Azure Region

4. Click Review + Create.

### Screenshot 8

*Resource Group Creation*

---

# 6. Resource Deployment

A Storage Account was deployed to test Azure resource provisioning.

## Steps

1. Search for Storage Accounts.
2. Select Create.
3. Configure:

* Subscription
* Resource Group
* Storage Account Name
* Region

4. Validate settings.
5. Deploy resource.

### Screenshot 9

*Storage Account Deployment Successful*

---

# 7. Billing and Cost Management

Azure provides tools to monitor spending.

## Access Billing

1. Search for Cost Management + Billing.
2. Open Cost Analysis.

### Screenshot 10

*Billing Dashboard*

---

# 8. Budget Alert Configuration

To avoid exceeding free limits, configure a budget alert.

## Steps

1. Open Cost Management.
2. Select Budgets.
3. Create New Budget.

### Configuration

| Setting         | Value            |
| --------------- | ---------------- |
| Budget Name     | Free-Tier-Budget |
| Amount          | $200             |
| Alert Threshold | 75%              |
| Alert Amount    | $150             |

4. Save configuration.

### Screenshot 11

*75% Budget Alert Configuration*

---

# 9. Security Configuration

## Microsoft Entra ID

Microsoft Entra ID manages identities and access permissions.

Functions:

* User Management
* Group Management
* Role Assignment
* Authentication Policies

### Screenshot 12

*Microsoft Entra ID Overview*

---

## Multi-Factor Authentication (MFA)

### Enable MFA

1. Open Microsoft Entra ID.
2. Select Users.
3. Choose Per-User MFA.
4. Enable MFA.

Benefits:

* Additional account protection
* Reduced risk of unauthorized access
* Improved compliance

### Screenshot 13

*MFA Enabled*

---

# Best Practices

* Enable MFA immediately.
* Monitor spending weekly.
* Use Resource Groups for organization.
* Delete unused resources.
* Review activity logs regularly.

---

# Troubleshooting

## Phone Verification Failed

* Confirm country code.
* Retry after several minutes.
* Use a different phone number.

## Payment Card Rejected

* Verify card supports online transactions.
* Ensure sufficient verification balance.

## Resource Deployment Failure

* Confirm region availability.
* Check naming requirements.
* Verify subscription status.

## Budget Alert Not Triggering

* Verify notification email.
* Check alert threshold settings.

---

# Completion Checklist

* [ ] Azure Account Created
* [ ] Email Verified
* [ ] Phone Verified
* [ ] Payment Method Added
* [ ] Azure Portal Explored
* [ ] Dashboard Customized
* [ ] Subscription Identified
* [ ] Resource Group Created
* [ ] Storage Account Deployed
* [ ] Billing Dashboard Reviewed
* [ ] 75% Budget Alert Configured
* [ ] Microsoft Entra ID Reviewed
* [ ] MFA Enabled
* [ ] Screenshots Added
* [ ] README Completed

---

# Conclusion

This project successfully demonstrated Azure account creation, portal navigation, billing management, security configuration, and deployment of a cloud resource while maintaining awareness of Azure Free Tier limitations and cost controls.
