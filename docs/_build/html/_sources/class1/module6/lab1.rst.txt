Lab 6.1 - Brief overview of our Ansible setup
---------------------------------------------

In this lesson we will look at a high-level overview of our Ansible setup. 
We'll also view what ASM policies currently exist on the BIG-IP and what ASM
policy, if any, are associated with ``hackazon_virtual`` virtual server. 

Task 1 - Inventory, playbooks, ansible.cfg
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

#. SSH to the Xubuntu host using the ``putty`` shorcut that can be found on the desktop.

#. Perform the following command to change the directory to the ``f5-ansible`` directory.

   ``cd f5-ansible``


#. Perform the following command to view the contents of the directory.

   ``ls -l``

   You'll see output similar to the following screenshot:

   .. image:: ../../_static/class1/module6/lab1-image001.png
      :align: center
      :scale: 50%

#. You'll see the inventory directory, the playbooks directory, and the ansible.cfg file.
   
   * Inventory_ - this is where we store our ``hosts`` file. The ``hosts`` file is where 
     you store the hosts that we will target when executing our playbooks. In our case this 
     is the BIG-IP, 10.1.1.245.
   .. _Inventory: https://docs.ansible.com/ansible/latest/user_guide/intro_inventory.html
   * Playbooks_ - this is where we store our ``playbooks`` which are used to deploy the code
     we've written to execute on our BIG-IP.
   .. _Playbooks: https://docs.ansible.com/ansible/latest/user_guide/playbooks.html
   * ansible.cfg_ - this is the configuration file for various settings to use with Ansible.  
   .. _ansible.cfg : https://docs.ansible.com/ansible/latest/reference_appendices/config.html#ansible-configuration-settings-locations


Task 2 - View ASM policies and view there are no ASM policies associated with hackazon_virtual virtual server
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

#. In your web browser, navigate to BIG-IP: ``https://10.1.10.20/``

#. Navigate to Main > Security > Application Security > Security Policies

   .. image:: ../../_static/class1/module6/lab1-image002.png
      :align: center
      :scale: 50%

   You'll notice the only policy that exists is the one you created in Lab5, iControlLX_Agility2018.

#. Navigate to Main > Local Traffic > Virtual Servers > Virtual Server List

#. Select ``hackazon_virtual`` then navigate to Security > Policies 

   .. image:: ../../_static/class1/module6/lab1-image003.png
      :align: center
      :scale: 50%

   .. NOTE:: You'll see there is no security policy attached to the virtual server. In the following
      sections we will attach a policy to the virtual server using Ansible. 



