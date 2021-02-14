Installation
========

Install the addon like every other addon by uploading it directly via SFTP or the control panel.

From control panel
========

.. image:: addon.png
  :width: 450
  :alt: Addons

For the control panel method you need php zip::

	sudo apt-get install php-zip
 	sudo yum install php-zip
	
Installing from archives must be explicitly enabled by adding the following line to src/config.php::

	$config['enableAddOnArchiveInstaller'] = true;
	
(S)FTP
========
Upload the contents of the "upload" folder to your root XenForo directory.
