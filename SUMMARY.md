# Table of contents

* [Introduction](README.md)
* [Setup Appsmith](setup/README.md)
  * [Docker](setup/docker/README.md)
    * [Email](setup/docker/email/README.md)
      * [Sendgrid](setup/docker/email/sendgrid.md)
      * [Amazon SES](setup/docker/email/amazon-ses.md)
    * [Google OAuth](setup/docker/google-login.md)
    * [Github OAuth](setup/docker/github-login.md)
    * [Google Maps](setup/docker/google-maps.md)
  * [Kubernetes](setup/kubernetes.md)
  * [AWS AMI](setup/aws-ami.md)
  * [Heroku](setup/heroku.md)
  * [Telemetry Opt-In](setup/telemetry.md)
* [Tutorial](tutorial-1/README.md)
  * [Part 1: Building a Simple UI](tutorial-1/part-1-creating-a-simple-view/README.md)
    * [The Appsmith Environment](tutorial-1/part-1-creating-a-simple-view/the-appsmith-environment.md)
    * [Creating your First Page](tutorial-1/part-1-creating-a-simple-view/creating-your-first-table.md)
  * [Part 2: Using forms](tutorial-1/part-2-using-forms/README.md)
    * [Creating your First Form](tutorial-1/part-2-using-forms/creating-a-form.md)
    * [Submitting the form](tutorial-1/part-2-using-forms/submitting-the-form.md)
  * [Part 3: Creating interactive views](tutorial-1/part-3-creating-interactive-views/README.md)
    * [Accessing properties between widgets](tutorial-1/part-3-creating-interactive-views/adding-edit-button.md)
    * [Writing your first API](tutorial-1/part-3-creating-interactive-views/writing-your-first-api.md)
    * [Configuring multiple actions on UI events](tutorial-1/part-3-creating-interactive-views/running-multiple-actions-on-submit.md)
* [How To Guides](how-to-guides/README.md)
  * [OAuth2 Authorization for Google Sheets](how-to-guides/oauth2-authorization-for-google-sheets.md)
  * [Share data across pages](how-to-guides/sharing-data-across-pages.md)
  * [Upload / Download Files from S3](how-to-guides/how-to-upload-to-s3.md)
  * [Migrate apps to a new instance](how-to-guides/backup-restore.md)
  * [Restricting Sign-up](how-to-guides/restricting-signup.md)
  * [Writing JavaScript in Appsmith](how-to-guides/writing-javascript-in-appsmith.md)
  * [Embed Appsmith into Existing Application](how-to-guides/embed-appsmith-into-existing-application.md)
  * [Whitelist Appsmith on AWS](how-to-guides/aws-whitelist.md)
  * [How to work with Local APIs on Appsmith](how-to-guides/how-to-work-with-local-apis-on-appsmith.md)
* [Debugging Errors](troubleshooting-guide/README.md)
  * [Action Errors](troubleshooting-guide/action-errors.md)
  * [JS Errors](troubleshooting-guide/widget-errors.md)
  * [Deployment Errors](troubleshooting-guide/deployment-errors.md)
  * [Application Errors](troubleshooting-guide/application-errors.md)
* [FAQs](faq.md)
* [Changelog](changelog.md)
* [Security](security.md)

## Core Concepts

* [Connecting to Data Sources](core-concepts/connecting-to-data-sources/README.md)
  * [Connect to Databases](core-concepts/connecting-to-data-sources/connecting-to-databases/README.md)
    * [Execute Queries](core-concepts/connecting-to-data-sources/connecting-to-databases/querying-a-database.md)
    * [Query Settings](core-concepts/connecting-to-data-sources/connecting-to-databases/query-settings.md)
  * [Connect to APIs](core-concepts/connecting-to-data-sources/connect-to-apis/README.md)
    * [API Authentication](core-concepts/connecting-to-data-sources/connect-to-apis/authentication/README.md)
      * [OAuth 2.0](core-concepts/connecting-to-data-sources/connect-to-apis/authentication/oauth2-authentication.md)
    * [Execute APIs](core-concepts/connecting-to-data-sources/connect-to-apis/execute-apis.md)
    * [API Settings](core-concepts/connecting-to-data-sources/connect-to-apis/api-settings.md)
    * [Signature Header](core-concepts/connecting-to-data-sources/connect-to-apis/signature-header-in-api-actions.md)
* [Displaying Data \(Read\)](core-concepts/displaying-data-read/README.md)
  * [Display Data in Tables](core-concepts/displaying-data-read/display-data-tables.md)
* [Capturing Data \(Write\)](core-concepts/capturing-data-write/README.md)
  * [Capture Form Data](core-concepts/capturing-data-write/capture-form-data.md)
* [Writing Code](core-concepts/writing-code/README.md)
  * [Creating Workflows](core-concepts/writing-code/workflows.md)
  * [Appsmith Framework](core-concepts/writing-code/appsmith-framework.md)
  * [External libraries](core-concepts/writing-code/ext-libraries.md)
* [Building Dynamic UI](core-concepts/dynamic-ui/README.md)
  * [Application Layout](core-concepts/dynamic-ui/application-layout.md)
  * [Controlling Widget Visibility](core-concepts/dynamic-ui/widget-visibility.md)
* [Access Control](core-concepts/access-control.md)

## Datasource Reference

* [Amazon S3](datasource-reference/querying-amazon-s3.md)
* [DynamoDB](datasource-reference/querying-dynamodb.md)
* [Elasticsearch](datasource-reference/querying-elasticsearch.md)
* [Firestore](datasource-reference/querying-firestore.md)
* [Google Sheets Integration](datasource-reference/querying-google-sheets.md)
* [MongoDB](datasource-reference/querying-mongodb/README.md)
  * [Mongo Query Syntax](datasource-reference/querying-mongodb/mongo-syntax.md)
* [MS SQL](datasource-reference/querying-mssql.md)
* [MySQL](datasource-reference/querying-mysql.md)
* [Postgres](datasource-reference/querying-postgres.md)
* [Redis](datasource-reference/querying-redis.md)
* [Redshift](datasource-reference/querying-redshift.md)

## Framework Reference

* [Cheat Sheet](framework-reference/cheat-sheet.md)
* [appsmith](framework-reference/appsmith.md)
* [Action](framework-reference/run.md)
* [Show Modal](framework-reference/show-modal.md)
* [Close Modal](framework-reference/close-modal.md)
* [Download](framework-reference/download.md)
* [Show Alert](framework-reference/show-alert.md)
* [Navigate To](framework-reference/navigateto.md)
* [Store Value](framework-reference/store-value.md)
* [Copy To Clipboard](framework-reference/copytoclipboard.md)
* [Reset Widget](framework-reference/resetwidget.md)

## Widget Reference

* [Button](widget-reference/button/README.md)
  * [Re-Captcha](widget-reference/button/google-recaptcha.md)
* [Chart](widget-reference/chart.md)
* [Checkbox](widget-reference/checkbox.md)
* [Container](widget-reference/container.md)
* [Datepicker](widget-reference/datepicker.md)
* [Dropdown](widget-reference/dropdown.md)
* [Filepicker](widget-reference/filepicker.md)
* [Form](widget-reference/form.md)
* [Image](widget-reference/image.md)
* [Input](widget-reference/input.md)
* [Maps](widget-reference/maps.md)
* [Modal](widget-reference/modal.md)
* [Radio](widget-reference/radio.md)
* [Rich Text Editor](widget-reference/rich-text-editor.md)
* [Switch](widget-reference/switch.md)
* [Tabs](widget-reference/tabs.md)
* [Table](widget-reference/table.md)
* [Text](widget-reference/text.md)
* [Video](widget-reference/video.md)

