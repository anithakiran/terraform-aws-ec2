# terrsform-aws-ecs
terraform module

#input 

* ami_id(optional) : ami_id is optional. default value = "ami-041e2ea9402c46c32".
* security_group_ids(optional) : list of security group ids. default value = "sg-0cc1d57ed8d1b996b".
* instance_type(optional) : default value is t3.micro.
* tags(optional) : dafualt value is empty.


#output

* public_ip : gives the public ip of the instance created.
* private_ip : gives the privates ip of the instane created.
* instance_id : gives the instance id created.
