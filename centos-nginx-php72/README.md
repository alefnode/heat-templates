# How to execute this stack #

openstack stack create --parameter instance_name=Prueba --parameter key_name=hadrianweb-auto --parameter flavor=Mini --parameter image_name="Centos 7" --parameter internal_net=cf57bce4-5518-4c07-a192-857045372155 --parameter internal_subnet=5249f549-dbad-44b9-aa29-068fa92dd467 --parameter domain_name=prueba.alefnode.com -t openstack-heat-nginx-php72.yml prueba
