# Hashicorp Homebrew Tap

This is a lamme xLabs' fork of https://github.com/hashicorp/homebrew-tap, so to enable us to install specific versions of Terraform.

## Install `terraform`

```shell
:; brew tap XLabs/hashicorp-tap
:; brew install xlabs/hashicorp-tap/terraform@1.8.5
```

## How to extract the official Homebrew formula

```shell
:; brew extract hashicorp/homebrew-tap/terraform --version=1.8.5 XLabs/hashicorp-tap
```
