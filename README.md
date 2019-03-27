Ensure that you have setup your environment with terraform and adjust the path to the generated terraform inventory file in
`inventory/terraform_inv.ini`

Run the deployment
`ansible-playbook -i inventory site.yml`

Run performance tests against your setup. Use the URL of your loadbalancer!
`ab -n 100 http://myloadbalancer-1645457-fra02.lb.bluemix.net/`
