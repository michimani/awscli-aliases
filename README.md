awscli-aliases
===

This is a collection of alias commands for the AWS CLI.

The AWS CLI alias feature is available in `v1.11.24` and later or `v2.0.0` and later.

# Usage

1. clone this repository

```bash
git clone https://github.com/michimani/awscli-aliases.git
```

2. make a directory for alias config of AWS CLI

```bash
mkdir -p ~/.aws/cli
```

3. copy alias file to config directory

```bash
cp awscli-aliases/alias ~/.aws/cli/alias
```

4. test

```bash
aws id
```

This command will allow you to retrieve your AWS account ID.