.. _api-create:

==============================
Creating and Managing API Keys
==============================

Skribble integrates with your existing tools, such as OneDrive, SharePoint, Google Drive or your industry solution via API. With the API connection, your team members can sign and get documents signed from the systems they already use. They can also invite external stakeholders or contracting parties to sign documents without creating a Skribble account. 

As an admin, you can generate and manage API keys for your company.  

For more information on integrating Skribble, please visit our `API documentation`_.

  .. _API documentation: https://api-doc.skribble.com/
  
  
Creating an API key
-------------------

- From your Business profile, go to **API keys** and click **Create API key** at the top right


.. image:: API_keys_step1_create.png
    :class: with-shadow


You can choose between 2 types of keys:

•	**Demo API keys** are for testing and development purposes. Signatures requested by such keys don't have any legal weight and are free of charge. The signing process works without 2FA.

•	**Production API keys** are used for live systems. Signatures requested by such keys will be invoiced. All costs of signature requests created with your API key will be charged to your company. 

- Select the key you need

- Add an API key description (optional)

.. image:: create_api_key.png
    :class: with-shadow


In the next step, you can view the API key (your password) and your username.


.. NOTE::
  The API key is your password and should be stored in a safe place. Unfortunately, we won't be able to recover it after you close the window.


.. image:: create_api_keys_step3_success_close.png
    :class: with-shadow



Managing API keys
-----------------

You can add an API key description and reset or delete an API key. To do so:

- Go to **API keys**

- Click the gearwheel icon on the right of the key, and a window with 3 options will open:

•	**Add description**: A short and meaningful description will work best if your company has several API keys in use. When adding a description, think of what the key is used for or what tool. **Example:** Testing OneDrive integration

•	**Reset API key**: Resetting is irreversible and will disable all the existing integrations with this key until the new API key is in place. Clicking **Reset API key** will generate a new key.

•	**Delete API key**: Deleting will remove all existing integrations irreversibly.


.. image:: manage_api_key.png
    :class: with-shadow


Need help with generating or managing your API keys? Drop us an e-mail at `support@skribble.com`_. 

  .. _support@skribble.com: support@skribble.com
