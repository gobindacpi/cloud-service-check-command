# cloud-service-check-command

~~~
Controller

systemctl status  neutron-server.service                                                                          
systemctl status  openstack-aodh-evaluator.service                                                                
systemctl status  openstack-aodh-listener.service                                                                 
systemctl status  openstack-aodh-notifier.service                                                                 
systemctl status  openstack-ceilometer-central.service                                                            
systemctl status  openstack-ceilometer-notification.service                                                   
systemctl status  openstack-cinder-api.service                                                                    
systemctl status  openstack-cinder-scheduler.service                                                              
systemctl status  openstack-glance-api.service                                                                    
systemctl status  openstack-heat-api-cfn.service                                                                  
systemctl status  openstack-heat-api.service                                                                      
systemctl status  openstack-heat-engine.service                                                                   
systemctl status  openstack-nova-api.service                                                                      
systemctl status  openstack-nova-conductor.service                                                                
systemctl status  openstack-nova-consoleauth.service                                                              
systemctl status  openstack-nova-novncproxy.service                                                               
systemctl status  openstack-nova-scheduler.service                                                                

compute

systemctl status openstack-ceilometer-compute.service                               
systemctl status openstack-cinder-volume.service                                    
systemctl status openstack-nova-compute.service                                     
systemctl status neutron-dhcp-agent.service                                         
systemctl status neutron-l3-agent.service                                           
systemctl status neutron-lbaasv2-agent.service                                      
systemctl status neutron-metadata-agent.service                                     
systemctl status neutron-openvswitch-agent.service                                  
systemctl status ovs-delete-transient-ports.service                                 
systemctl status ovs-vswitchd.service                                               
systemctl status ovsdb-server.service                                               
systemctl status libvirtd.service 

CEPH: 

ceph health detail 
ceph -s
~~~
