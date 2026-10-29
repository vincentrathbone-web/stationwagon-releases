# Stationwagon releases

Downloads for Stationwagon, an online radio station you run on ordinary web hosting.

The newest files are always under [Releases → Latest](https://github.com/vincentrathbone-web/stationwagon-releases/releases/latest):

| File | What it is for |
|---|---|
| `setup.php` | **A site without WordPress.** Upload this one file to your web space (for example with cPanel → File Manager) and open it in your browser, e.g. `https://example.com/setup.php`. It checks the server, asks where the station should live (a subfolder like `/radio`, that folder, or a new subdomain), downloads the station, and hands over to its installer. It works for an hour after you upload it, and removes itself when done. |
| `stationwagon-wordpress.zip` | **A WordPress site.** In WordPress go to Plugins → Add New → Upload Plugin, choose this file, activate it, then open **Stationwagon** in the admin menu. |
| `stationwagon.zip` | The station itself. `setup.php` downloads this for you; you don't need it yourself. |

Stationwagon needs PHP 8.1 or newer and a MySQL or MariaDB database.
