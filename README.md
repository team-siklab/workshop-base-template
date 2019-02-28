Module 1: The first sample module
===

This is an example module.
The page title should include the **module number** and a short but descriptive title.

You should provide an introductory paragraph that sets some context for the use case to be covered.
If possible, this should tie into the story being told through the workshop, if any.

Consider providing CloudFormation templates for launching the module's finished solution
to allow students to opt into just moving to the next module directly.

Region| Launch
------|-----
US East (N. Virginia) | [![Launch Module 1 in us-east-1](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/images/cloudformation-launch-stack-button.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=your-stack-name&templateURL=https://s3.amazonaws.com/wildrydes-us-east-1/WorkshopTemplate/1_ExampleTemplate/example.yaml)
US West (Oregon) | [![Launch Module 1 in us-west-2](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/images/cloudformation-launch-stack-button.png)](https://console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/new?stackName=your-stack-name&templateURL=https://s3.amazonaws.com/wildrydes-us-west-2/WorkshopTemplate/1_ExampleTemplate/example.yaml)

<details>
  <summary><strong>CloudFormation Launch Instructions (expand for details)</strong></summary>
  1. Click the **Launch Stack** link above for the region of your choice.
  2. Click **Next** on the Select Template page.
  3. ...
</details>

## Solution Architecture

Provide as description of the architecture of the solution that the students will build.
Strongly consider putting in a diagram and a short description of the components used.

To add an image, store your images in a `__assets` directory on the branch's base directory.
You can embed an image into this document using:

```
![some image description](__assets/image.jpg)
```

## Implementation Overview

This section should provide students with the high level steps required to complete the solution.
It should enumerate all the components and major configuration tasks required, 
but should not get to the detail of providing step-by-step instructions 
for which buttons to click, etc.

> Sample:

The following provides an overview of the steps needed to complete this module.
This section is intended to provide enough details to complete the module for students
who are already familiar with the AWS console and CLI.
If you'd like detailed, step-by-step instructions, please use the heading links 
to jump to the appropriate section.

### Create an S3 Bucket.

Use the console or CLI to create an S3 bucket.
If you'd like to use a custom domain to host the site, make sure you name your bucket
using the full domain name (e.g. unicorns.domain.com).

### Upload content.

Copy the content of the example bucket, `xyz`. 
There is also a ZIP archive available at `xyz` that you can download locally and extract
in order to upload the content via the console.

### Add a bucket policy to allow public reads.

Bucket policies can be updated via the console or the CLI.
You can use the provided policy document or build your own.
See the documentation for more information.


## Summary

At the end of the module, provide a short summary of what was accomplished and built.
No need to go into detail.
This is a good place to mention nice-to-know tidbits, or future improvements the students
can perform on their solutions in their own time.

Provide a link to the next module's base branch here as well.

**Next:** [Nuke your AWS account.](/team-siklab/workshop-base-template/tree/master)