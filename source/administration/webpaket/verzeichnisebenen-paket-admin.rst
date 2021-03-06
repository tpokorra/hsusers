===========================
Verzeichnisebene Paketadmin
===========================

.. |date| date:: %d.%m.%Y
.. |time| date:: %H:%M

:Authors: - Uwe Müller
          - Dominic Schlegel

:Date: |date|, |time|

Das Home-Verzeichnis des :doc:`Paket-Admins<../benutzer/paket-admin>` umfasst folgende Verzeichnisse:

+-----------------+--------+---------+----------+--------------------------------------------------------------------------+
| Berechtigungen  | Nutzer | Gruppe  | Ordner   |  Erläuterung                                                             |
+=================+========+=========+==========+==========================================================================+
| drwx-----       | xyz00  | xyz00   | .bak     |  Ablage komprimierter Backups der Datenbanken und Cronjobs.              |
+-----------------+--------+---------+----------+--------------------------------------------------------------------------+
| dr-xr-x--T      | httpd  | xyz00   | doms     |  Ablage der Paketdomain xyz00.hostsharing.net.                           |
+-----------------+--------+---------+----------+--------------------------------------------------------------------------+
| drwx------      | xyz00  | xyz00   | etc      |  Ablage für eigene Konfigurationsdateien.                                |
+-----------------+--------+---------+----------+--------------------------------------------------------------------------+
| drwxr-xr-x      | xyz00  | xyz00   | users    |  Ablage der angelegten Nutzer                                            |
+-----------------+--------+---------+----------+--------------------------------------------------------------------------+
| drwxr-x---      | xyz00  | xyz00   | var      |  Ablage von Logfiles (z.B. Web-Logs, Traffic-Logs)                       |
+-----------------+--------+---------+----------+--------------------------------------------------------------------------+
| drwx------      | xyz00  | xyz00   | Maildir  |  Mailordner des :doc:`Paket-Admin</administration/benutzer/paket-admin>`.|
+-----------------+--------+---------+----------+--------------------------------------------------------------------------+


