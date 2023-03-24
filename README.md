# Terraform Plan

## Usage

```yaml

    - name: terraform plan
        uses: clockwork-marketing-uk/actions-terraform-plan@1
        with:
          path: my-terraform-config
          label: production
          var_file: env/prod.tfvars
          backend_config_file: env/prod.backend
          github-token: ${{ secrets.GITHUB_TOKEN }}

```
