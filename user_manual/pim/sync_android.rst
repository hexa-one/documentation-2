==========================
Synchronizing with Android
==========================

Files and notifications
-----------------------

1. Install the Nextcloud Android client `from Google Play Store <https://play.google.com/store/apps/details?id=com.nextcloud.client>`_ or 
   `from F-Droid <https://f-droid.org/de/packages/com.nextcloud.client/>`_.
2. Start the app. There are two ways of setting it up:

   *Either*: enter
   your server URL, continue, enter your user name and password and
   confirm to grant access.

   *Or*: In Nextcloud's web GUI, go to the
   `user preferences <../userpreferences.html>`_, go to
   **Security**. Generate an App password, click "Generate QR code" and
   tap the QR scanner icon in the Nextcloud app, point your phone's
   camera towards the screen.

Contacts and Calendar
---------------------

With the Nextcloud mobile app
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Install `DAVx⁵ (formerly known as DAVDroid) <https://www.davx5.com/download/>`_ on your Android device, 
   `from Google Play Store <https://play.google.com/store/apps/details?id=at.bitfire.davdroid>`_ or 
   `from F-Droid <https://f-droid.org/de/packages/at.bitfire.davdroid/>`_.
2. In the Nextcloud mobile, go
   to **Settings** / **More**, tap on "**Sync calendars & contacts**".
3. Now, DAVx⁵ will open Nextcloud's Webflow login window, where you
   will have to enter your credentials and grant access.
4. DAVx⁵ will open and ask you to create an account. Set the account
   name to one of your choosing, and set **Contact Group Method** to
   **Groups are per-contact categories**.
5. After this, DAVx⁵ will close and the Nextcloud app reappears. In
   order to finish setup, you have to manually launch DAVx⁵ again.
6. Tap on the icon for the account DAVx⁵ has just created, when requested grant DAVx⁵ access
   to your calendars and contacts. Optionally install `OpenTasks <https://play.google.com/store/apps/details?id=org.dmfs.tasks>`_  and
   grant DAVx⁵ access to your tasks, too.
7. When you tap the icon for the account DAVx⁵ has set up, it will
   discover the available address books and calendars. Choose which
   ones you want to synchronize and finish.


Without the Nextcloud mobile app
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
If you don't want to install the Nextcloud mobile app, the following
steps are required:

1. Install `DAVx⁵ (formerly known as DAVDroid) <https://www.davx5.com/download/>`_ on your Android device, 
   `from Google Play Store <https://play.google.com/store/apps/details?id=at.bitfire.davdroid>`_ or 
   `from F-Droid <https://f-droid.org/de /packages/at.bitfire.davdroid/>`_.
2. Optionally install `OpenTasks <https://play.google.com/store/apps/details?id=org.dmfs.tasks>`_.
3. Create a new account ("+" button).
4. Select **Connection with URL and username**.
   **Base URL:** URL of your Nextcloud instance (e.g. ``https://sub.example.com/remote.php/dav``) and 
   **Contact Group Method:** as credentials.
5. Choose the option ``Groups are per-contact categories``.
6. Click **Connect**.
7. Select the data you want to sync.
8. When requested, grant access permissions to DAVx⁵ for your
   contacts, calendars and optionally tasks.

.. note:: Enter your email address as DAVx⁵ account name (mandatory if you want
   to be able to send calendar invitation). If your email address is
   registered in your Nextcloud preferences and you have set up your
   account using the Nextcloud mobile app, this all should be aready the case.


.. tip:: DAVx⁵ lists the calendar subscriptions made through the Nextcloud Calendar app, but you need to install the `ICSx⁵ (formerly known as ICSDroid) <https://icsx5.bitfire.at/>`_ app on your Android device, `from the Google Play Store <https://play.google.com/store/apps/details?id=at.bitfire.icsdroid>`_ or `from F-Droid <https://f-droid.org/packages/at.bitfire.icsdroid/>`_ to sync them.
