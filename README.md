# pulumi-challenge-03

## For anyone use an AWS root account with MFA for sts

```shell
aws iam list-mfa-devices
ws sts get-session-token --serial-number [SerialNumber] --token-code [Token from MFA device] --duration-seconds 86400
```
