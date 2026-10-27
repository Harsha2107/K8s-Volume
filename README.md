you can check the pv & pvc concepts here, 
we need to repalce the volume id with EBS volume we create in cloud in pv.yml

once we are done we can also verify if the data being replicated across the containers or not
to entre into an container
--> kubectl exec -it dp-84545bfdd4-4p6hg -c cont1 -- bash

create few files and then exit from this container and go to other container and then check the files being replicated there or not
