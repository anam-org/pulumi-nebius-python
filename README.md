# Pulumi Nebius Python

This is a python binding for terraform-provider-nebius generated using [Any terraform provider](https://www.pulumi.com/registry/packages/terraform-provider/)

## Installation

    poetry install

## Usage

    import pulumi_nebius as nebius

    nebius.Provider(
        "nebius",
    )

## Authentication

Follow the instructions in the [Nebius Terraform Provider documentation](https://docs.nebius.com/terraform-provider/authentication)

    # Quick start via user account
    export NEBIUS_IAM_TOKEN=$(nebius iam get-access-token)

