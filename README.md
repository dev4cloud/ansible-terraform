Ensure that you have setup your environment with terraform and adjust the path to the generated terraform inventory file in
`inventory/terraform_inv.ini`

Run the deployment
`ansible-playbook -vvvv -i inventory site.yml`
