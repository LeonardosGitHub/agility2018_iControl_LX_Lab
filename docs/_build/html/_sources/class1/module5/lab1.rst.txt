Lab 5.1 - Enable iControlLX extension management via GUI
--------------------------------------------------------

iControl LX extensions are distributed as RPMs (RedHat Package Management
system), in this lesson we will enable management of RPMs using the GUI. 


Task 1 - View iControlLX management is NOT available via the GUI
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

iControl LX extensions can be installed on either the BIG-IP or iWorkflow
platform. For this lab, we will use BIG-IP.

Perform the following steps to complete this task:

#. In your web browser, navigate to BIG-IP: ``https://10.1.10.20/``


#. Navigate to Main > iApps

   * You'll notice that iControlLX extension management is not available.

   .. image:: ../../_static/class1/module5/lab1-image001.png
      :align: center
      :scale: 50%


Task 2 - SSH to BIG-IP to enable iControlLX management via the GUI
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Perform the following steps to complete this task:

#. Find and open the application ``putty`` on the desktop, using the saved session 
   SSH to the BIG-IP_A.

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





