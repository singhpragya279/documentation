# Foundational Trust Provider

## Overview

This guide enables the Foundational Trust providers to use the PMP portal effectively. Below is the workflow:

*	Partner self-register through the portal.
*	Partner admin and uploads CA certificate.
*	Partner admin/ Partner uploads partner certificate.
*	Partner admin/ Partner creates FTM.
*	Partner admin/ Partner uploads certificate from menu before approval/ rejection.
*	Partner admin approves/ rejects the FTM.

### Self-registration

* The partner can register themselves on MOSIP PMP portal by clicking **Register** on the landing page.
* They need to fill up a form with the details below:
    * First and Last name
    * Organization Name
    * Partner type (Device Provider)
    * Address, e-mail, phone number
    * Username and password

![](_images/ftm-partner-self-register1.PNG)  ![](_images/ftm-partner-self-register2.PNG)

To view the details entered, click **Home** to see the dashboard.

![](_images/ftm-partner-home-page.PNG)

### Upload of Certificates

#### CA Certificate upload

The Partner admin needs to upload the CA certificate to enable the partner for using the portal. To do so, the Partner admin:

1. Clicks **Upload CA Certificate** option on the left navigation pane of the partner portal.
2. Selects the Partner Domain as FTM.
3. Chooses the certificate to upload (only files with extensions as .cer or .pem).
4. Clicks **Upload**. 

The uploaded certificates can be viewed by clicking on `View Certificates-> View`.

#### Partner Certificate upload

Similarly, the Partner certificates can be added by the Partner admin/ partner.

The certificate can be uploaded by clicking **Home-> Upload Certificate -> Upload**.

![](_images/ftm-partner-cert-upload.PNG)

![](_images/ftm-partner-cert-upload-success.PNG)

The certificate can be viewed by clicking **Home-> View Certificate ->View**.

![](_images/ftm-partner-view-cert.PNG)

### FTM Details

#### Creating FTM Details

The partner can create FTM details by,
1. Clicking FTM Details -> Create FTM
2. Filling up the information like Partner Name, Make and Model.
3. Clicking Save.

![](_images/ftm-partner-makemodel-view.PNG)

![](_images/ftm-partner-create-make-model.PNG)

![](_images/ftm-partner-create-makemodel-success.PNG)

#### FTM Certificate Upload

The partner can upload FTM certificates by,
1. Selecting **Upload Certificate** option from the Actions menu against the FTM created.
2. Entering the Partner Domain as FTM and choosing the certificate file.
3. Clicking Upload.

![](_images/ftm-partner-chip-sub-menu.PNG)

![](_images/ftm-partner-cert-upload.PNG)

#### Approval/ rejection of the certificate

The Partner Admin can choose to approve/ reject the FTM certificate uploaded. Below illustrates the workflow:

![](_images/partner-admin-ftm-details-view-page.PNG)

![](_images/partner-admin-ftm-details-actions.PNG)

![](_images/partner-admin-ftm-details-approve-action.PNG)

Finally, you can see the FTM activated.

![](_images/ftm-active.png)
