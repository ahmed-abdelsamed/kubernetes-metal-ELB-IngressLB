# kubernetes-metal-ELB-IngressLB


#for using Eternal LB for masters nodes , edit  path /opt/kubespray/inventory/mycluster/group_vars/all/

'
## External LB example config
apiserver_loadbalancer_domain_name: "bootstrap.coffee.me"

loadbalancer_apiserver:                                                               

  address: 192.168.6.200

  port: 6443

loadbalancer_apiserver_localhost: false

'
