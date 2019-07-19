# aws-well-architected-cross-account-access
Flexible template for configuring cross account access to the AWS Console Well Architected Tool

To deploy this into Oregon (us-west-2) please use the link below:

__<a href="https://us-west-2.console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/create/review?templateURL=https://mikeapted-github.s3.amazonaws.com/aws-well-architected-cross-account-access/well-architected-cross-account.yaml&stackName=WellArchitectedReviewRole">Deploy the IAM Role</a>__

You will need to input:

* __the accountID__ that you want to authorize to assume that role
* __the access type__: ReadOnly or FullAccess
* __the role name__ (leave as default in most cases)

_You need to be logged into the AWS account where you completed the Well Architected Review._

_If you like to execute the CloudFormation script within another region than Oregon use:_

* <a href="https://eu-west-1.console.aws.amazon.com/cloudformation/home?region=eu-west-1#/stacks/create/review?templateURL=https://mikeapted-github.s3.amazonaws.com/aws-well-architected-cross-account-access/well-architected-cross-account.yaml&stackName=WellArchitectedReviewRole">Deploy the IAM Role in EU (Ireland)</a>
* <a href="https://us-east-2.console.aws.amazon.com/cloudformation/home?region=us-east-2#/stacks/create/review?templateURL=https://mikeapted-github.s3.amazonaws.com/aws-well-architected-cross-account-access/well-architected-cross-account.yaml&stackName=WellArchitectedReviewRole">Deploy the IAM Role in US East (Ohio)</a>
* <a href="https://us-east-1.console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/create/review?templateURL=https://mikeapted-github.s3.amazonaws.com/aws-well-architected-cross-account-access/well-architected-cross-account.yaml&stackName=WellArchitectedReviewRole">Deploy the IAM Role in US East (N. Virginia)</a>
* <a href="https://ap-southeast-2.console.aws.amazon.com/cloudformation/home?region=ap-southeast-2#/stacks/create/review?templateURL=https://mikeapted-github.s3.amazonaws.com/aws-well-architected-cross-account-access/well-architected-cross-account.yaml&stackName=WellArchitectedReviewRole">Deploy the IAM Role in Asia Pacific (Sydney)</a>
