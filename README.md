# pre-commit-tf

Terraform [pre-commit](http://pre-commit.com/) hook which runs `terraform fmt` and `terraform validate` on `*.tf` files.

## Usage

Example `<git_project>/.pre-commit-config.yaml` for in your terraform project:

```
-   repo: git@github.com:OblivionCloudControl/pre-commit-tf.git
    rev: v0.0.3
    hooks:
    -  id: terraform_fmt
    -  id: terraform_validate
```
