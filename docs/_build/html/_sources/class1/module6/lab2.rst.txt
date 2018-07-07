Lab 6.2 - Run playbook to create ASM policy and associate with virtual server
----------------------------------------------------

Now that the GUI is able to manage the iControLX Extensions rpm packages.
Let's upload the rpm package from the desktop to the BIG-IP.


Task 1 - Upload rpm package to BIG-IP
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

#. In your web browser, navigate to BIG-IP: ``https://10.1.10.20/``

#. Navigate to Main > iApps > Package Management LX then select Import from the right.

   .. image:: ../../_static/class1/module5/lab2-image001.png
      :align: center
      :scale: 50%

#. Select "Choose File" and navigate to Desktop and select:

   ``SecurityAdd-0.2-002.noarch.rpm``

#. Select "Upload" and the rpm package will be added to the BIG-IP.

   .. image:: ../../_static/class1/module5/lab2-image002.png
      :align: center
      :scale: 50%

   .. NOTE:: You can also create and upload rpm packages using BIG-IP iControl
      REST. See the following article on DevCentral: `Deploying an iControl Extension`_

   .. _Deploying an iControl Extension: https://devcentral.f5.com/Wiki/iControlLX.HowToSamples_deploy_icontrol_extension.ashx

#. You will now see the package installed on the BIG-IP.

   .. image:: ../../_static/class1/module5/lab2-image003.png
      :align: center
      :scale: 50%



