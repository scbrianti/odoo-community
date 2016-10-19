===========================================================
All-IP Two-Factor SMS & Call Authentication (2FA)(End User)
===========================================================

App Installation on Odoo:
=========================

:menuselection:`[Odoo] --> All Apps`
------------------------------------

- `Login to Odoo Instance <SVN/SaBRO%2520Documentation/_build/telecom/user_guide/Login_to_SaBRO.html>`__  using Admin credentials.

.. image:: ./media/DigitsAuthenticationEndUser0.jpg
   :align: center

|
-  Click on Apps

.. image:: ./media/DigitsAuthenticationEndUser1.jpg
   :align: center

|
-  Search for the module. Ex-Search: Authentication

-  List of authentication apps could be seen

.. image:: ./media/DigitsAuthenticationEndUser2.jpg
   :align: center 

|   
-  Click on the "All-IP Two-Factor SMS & Call Authentication (2FA)" app.

-  App details will be shown

-  Click on Install

.. image:: ./media/DigitsAuthenticationEndUser3.jpg
   :align: center    


App Configuration on Odoo:
==========================

:menuselection:`All Apps --> Settings`
--------------------------------------

-  Once installed Click goto All Apps

.. image:: ./media/DigitsAuthenticationEndUser4.jpg
   :align: center 

|
-  Click on Settings.

.. image:: ./media/DigitsAuthenticationEndUser5.jpg
   :align: center 
 
:menuselection:`Settings --> Digits Configuation --> Configuration`
-------------------------------------------------------------------

-  Click on "Configuration" under Digits Configuation

.. image:: ./media/DigitsAuthenticationEndUser6.jpg
   :align: center

|
-  Click on Create

.. image:: ./media/DigitsAuthenticationEndUser7.jpg
   :align: center

|
-  Click on "Request Digits Customer Key".

.. image:: ./media/DigitsAuthenticationEndUser8.jpg
   :align: center

|
-  Enter the cusumer key received on Email and Save.

.. image:: ./media/DigitsAuthenticationEndUser9.jpg
   :align: center


:menuselection:`[User] --> Preferences --> Enable 2F Login`
-----------------------------------------------------------

-  Goto Preferences from top right user menu

.. image:: ./media/DigitsAuthenticationEndUser10.jpg
   :align: center

|
-  Check "Enable 2F Login".

.. image:: ./media/DigitsAuthenticationEndUser11.jpg
   :align: center

|
-  NOTE: User needs to have their mobile number present in their [All apps] -> Contacts -> [Contact] page.

.. image:: ./media/DigitsAuthenticationEndUser12.jpg
   :align: center


:menuselection:`[All Apps] --> Settings --> Users --> [User]`
-------------------------------------------------------------

-  To enable "2F Login" for other users.

-  Login to odoo instance with appropriate(admin) priviledges.

-  Click on Settings under All apps.

-  Click on Users and select the user in consideraion.

.. image:: ./media/DigitsAuthenticationEndUser13.jpg
   :align: center

|
:menuselection:`[User] --> Preferences --> Enable 2F Login`
-----------------------------------------------------------

-  On the selected User configuration page, click on "Edit".

.. image:: ./media/DigitsAuthenticationEndUser14.jpg
   :align: center

|   
-  Goto Preferences tab and check "Enable 2F Login" and Save.

.. image:: ./media/DigitsAuthenticationEndUser15.jpg
   :align: center   

-  NOTE: User in consideration should have mobile number present in their [All apps] -> Contacts -> [Contact] page.