Lab 2.3 - Advanced (raw JSON)
-----------------------------

Task 1 - View the JSON Representation of a User Account
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Perform the following steps to complete this task:

#. Navigate to your list of user accounts: (You may need to login again as ``admin/admin``)

   ``https://10.1.1.245/mgmt/shared/authz/users/presentation#/``

#. Click on the user you created earlier (``user42``).

#. Click the :guilabel:`Edit` button.

#. Click the :guilabel:`Advanced` button. A JSON input window will appear:

   .. image:: ../../_static/class1/module2/lab3-image001.png
      :align: center
      :scale: 50%

#. Note that the values in JSON match those presented above in the
   ``/presentation#/`` view.

Task 2 - Modify a User Account's JSON Representation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Perform the following steps to complete this task:

#. In the ``JSON Input:`` field, edit the value of ``displayName`` by changing ``User 42`` to ``Modified User 42``.

#. Note that it automatically changes in the ``/presentation#/`` view above.

#. Click :guilabel:`Save` or :guilabel:`Cancel`.

#. Click ``Parent`` to return to the list of users.

Task 3 - Delete the User
^^^^^^^^^^^^^^^^^^^^^^^^

Perform the following steps to complete this task:

#. Click the trash can icon next to the user you created earlier (``user42``) to delete this user account.
