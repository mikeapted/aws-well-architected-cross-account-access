# aws-well-architected-cross-account-access
Flexible template for configuring cross account access to the AWS Console Well Architected Tool

To deploy this please use the link below:

__<a href="https://us-west-2.console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/create/review?templateURL=https://well-architected-review-role.s3.amazonaws.com/well-architected-cross-account.yaml&stackName=WellArchitectedReviewRole">Deploy the IAM Role</a>__

You have to choose:

* __the role name__
* __the accountID__ that you want to authorize to assume that role
* __the access type__: ReadOnly or FullAccess

_You need to be logged in the account where you want the Well Architected Review to be created within you browser._

_If you like to execute the CloudFormation script within another region than Oregon use:_

* <a href="https://eu-west-1.console.aws.amazon.com/cloudformation/home?region=eu-west-1#/stacks/create/review?templateURL=https://well-architected-review-role.s3.amazonaws.com/well-architected-cross-account.yaml&stackName=WellArchitectedReviewRole">Deploy the IAM Role in EU (Ireland)</a>
* <a href="https://us-east-2.console.aws.amazon.com/cloudformation/home?region=us-east-2#/stacks/create/review?templateURL=https://well-architected-review-role.s3.amazonaws.com/well-architected-cross-account.yaml&stackName=WellArchitectedReviewRole">Deploy the IAM Role in US East (Ohio)</a>
* <a href="https://us-east-1.console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/create/review?templateURL=https://well-architected-review-role.s3.amazonaws.com/well-architected-cross-account.yaml&stackName=WellArchitectedReviewRole">Deploy the IAM Role in US East (N. Virginia)</a>
* <a href="https://ap-southeast-2.console.aws.amazon.com/cloudformation/home?region=ap-southeast-2#/stacks/create/review?templateURL=https://well-architected-review-role.s3.amazonaws.com/well-architected-cross-account.yaml&stackName=WellArchitectedReviewRole">Deploy the IAM Role in Asia Pacific (Sydney)</a>
