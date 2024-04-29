<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-pro/s3-secure/blob/master/docs/one-account.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

## One AWS Account Commands

Here are the summarized commands if you're using the One AWS account strategy.

## Deploy

Let's deploy now with [lono deploy](https://lono.cloud/reference/lono-cfn-deploy/).

    LONO_ENV=development lono cfn deploy s3-secure-development --blueprint s3-secure --sure --no-wait
    LONO_ENV=production  lono cfn deploy s3-secure-production  --blueprint s3-secure --sure --no-wait
