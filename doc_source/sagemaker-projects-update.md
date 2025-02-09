# Update an MLOps Project in Amazon SageMaker Studio<a name="sagemaker-projects-update"></a>

This procedure demonstrates how to update an MLOps project in Amazon SageMaker Studio\. You can update the **Description**, template version, and template parameters\.

**Prerequisites**
+ An AWS SSO or IAM account to sign in to Studio\. For information, see [Onboard to Amazon SageMaker Domain](gs-studio-onboard.md)\.
+ Basic familiarity with the Studio user interface\. For information, see [Amazon SageMaker Studio UI Overview](studio-ui.md)\.

**To update a project in Studio**

1. Sign in to Studio\. For more information, see [Onboard to Amazon SageMaker Domain](gs-studio-onboard.md)\.

1. In the Studio sidebar, choose the **SageMaker resources** icon \( ![\[Image NOT FOUND\]](http://docs.aws.amazon.com/sagemaker/latest/dg/images/icons/Components_registries.png)\)\.

1. Select **Projects** from the dropdown list\.

   A list of your projects appears\.

1. You can open the **Project update** dialog box in one of the following ways:

   1. You can open it from the projects list\.

      Right\-click the target project and choose **Update** from the dropdown list\.

   1. You can open it from the project tab\.

      1. Double\-click the project in the projects list\.

      1. Choose **Update** from the **Actions** menu in the upper\-right corner of the project tab\.

1. In the **Update project** dialog box, you can edit the **Description**, template version, and template parameters\.

1. Choose **Show Diff**\.

   A dialog box displays your original and updated project settings\. Any change in your project settings can modify or delete resources in the current project\. The dialog box displays these changes as well\.

1. You may need to wait a few minutes for the **Update** button to become active\. Choose **Update**\.

1. The project update may take a few minutes to complete\. Select **Settings** in the project tab and ensure the parameters have been updated correctly\.