Lab 6.2 - Run playbook to create ASM policy and associate with virtual server
----------------------------------------------------

In this lesson we will use Ansible to deploy a new ASM policy and attach that policy
to an existing virtual server. 


Task 1 - Run playbook from the Ubuntu host
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

#. On your ubuntu host you should be at a prompt that looks like this: 
   
   ``external_user@xubuntu-vm:~/f5-ansible$``
   
   You should be in the "f5-ansible" directory.


#. At the prompt type the following:
   
   ``ansible-playbook playbooks/ASM_create_apply.ym``

   .. NOTE:: information



   .. image:: ../../_static/class1/module5/lab2-image003.png
      :align: center
      :scale: 50%



