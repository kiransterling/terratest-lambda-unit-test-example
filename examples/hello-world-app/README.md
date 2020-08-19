

## Running this example manually

1. Sign up for [AWS](https://aws.amazon.com/).
1. Configure your AWS credentials using one of the supported methods for AWS CLI tools, 
   such as setting the `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY` environment variables. 
1. Install [Terraform](https://www.terraform.io/) and make sure it's on your `PATH`.
1. Run `terraform init`.
1. Run `terraform apply`.
1. This module will output the URL of the "Hello, World" app at the end of `apply`. Try this URL out in your browser or
   via `curl` to see if it's working!
1. When you're done, run `terraform destroy`.

## Running automated tests against this example

1. Sign up for [AWS](https://aws.amazon.com/).
1. Configure your AWS credentials using one of the supported methods for AWS CLI
   tools such as setting the `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY` environment variables. 
1. Install [Terraform](https://www.terraform.io/) and make sure it's on your `PATH`.
1. Install [Golang](https://golang.org/), minimum version `1.13`.
1. `cd test`
1. To run the unit test for this example: `go test -v -timeout 15m -run '^TestHelloWorldAppUnit$'`
