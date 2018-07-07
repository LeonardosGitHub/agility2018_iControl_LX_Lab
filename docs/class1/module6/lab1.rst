Lab 6.1 - Brief overview of our Ansible setup
---------------------------------------------

In this lesson we will look at a high-level overview of our Ansible setup. 
We'll also view what ASM policies currently exist on the BIG-IP and what ASM
policy, if any, are associated with ``hackazon_virtual`` virtual server. 

Task 1 - Inventory, playbooks, ansible.cfg
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

#. SSH to the Ubuntu host using the putty shorcut that can be found on the Desktop.

#. Perform the following command to change the directory to the ``f5-ansible`` directory.

   ``cd f5-ansible``


#. Perform the following command to view the contents of the directory.

   ``ls -l``

   .. image:: ../../_static/class1/module5/lab1-image001.png
      :align: center
      :scale: 50%


Task 2 - SSH to BIG-IP to enable iControlLX management via the GUI
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Perform the following steps to complete this task:

#. Using putty SSH to the BIG-IP_A.

#. At the bash shell enter the following command:

   ``touch /var/config/rest/iapps/enable``

#. Once the above command is issued, the BIG-IP can now manage iControlLX extensions via the GUI.


Task 3 - View iControlLX management is now available via the GUI
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Perform the following steps to complete this task:

#. In your web browser, navigate to BIG-IP: ``https://10.1.10.20/``

#. Navigate to Main > iApps

   * You'll notice that iControlLX extension management is now available.

   .. image:: ../../_static/class1/module5/lab1-image002.png
      :align: center
      :scale: 50%





