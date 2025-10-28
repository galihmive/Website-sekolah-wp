# WordPress
<p align="center">
   <img src="https://wordpress.org/wp-content/themes/pub/wporg/images/wp-logo-blue.png" alt="WordPress Logo" width="200">
</p>
---

## 📝 First Things First

Welcome. WordPress is a very special project to me. Every developer and contributor adds something unique to the mix, and together we create something beautiful that I am proud to be a part of. Thousands of hours have gone into WordPress, and we are dedicated to making it better every day. Thank you for making it part of your world.

— *Matt Mullenweg*

---

## ⚙️ Installation: Famous 5-Minute Install

1. Unzip the package in an empty directory and upload everything.
2. Open [`wp-admin/install.php`](wp-admin/install.php) in your browser. It will take you through the process to set up a `wp-config.php` file with your database connection details.
   - If for some reason this does not work, open `wp-config-sample.php` with a text editor and fill in your database connection details.
   - Save the file as `wp-config.php` and upload it.
   - Open [`wp-admin/install.php`](wp-admin/install.php) again.
3. Once the configuration file is set up, the installer will set up the tables needed for your site.
4. **If you did not enter a password, note the password given to you.**  
   If you did not provide a username, it will be `admin`.
5. The installer will then send you to the [login page](wp-login.php).  
   Sign in with the username and password you chose during installation.

---

## 🔁 Updating

### Using the Automatic Updater
1. Open [`wp-admin/update-core.php`](wp-admin/update-core.php) in your browser and follow the instructions.
2. That’s it!

### Updating Manually
1. Back up any files you’ve modified.
2. Delete your old WordPress files, keeping modified ones.
3. Upload the new files.
4. Visit [`wp-admin/upgrade.php`](wp-admin/upgrade.php) in your browser.

---

## 🔄 Migrating from Other Systems

WordPress can [import from a number of systems](https://developer.wordpress.org/advanced-administration/wordpress/import/).  
First, get WordPress installed and working as described above, then use the [import tools](wp-admin/import.php).

---

## 💻 System Requirements

- [PHP](https://www.php.net/) **7.2.24** or greater  
- [MySQL](https://www.mysql.com/) **5.5.5** or greater

### Recommended
- PHP **8.3** or greater  
- MySQL **8.0** or [MariaDB](https://mariadb.org/) **10.6** or greater  
- Apache module [mod_rewrite](https://httpd.apache.org/docs/2.2/mod/mod_rewrite.html)  
- [HTTPS](https://wordpress.org/news/2016/12/moving-toward-ssl/) support  
- A link to [wordpress.org](https://wordpress.org/) on your site

---

## 🌐 Online Resources

If you have any questions not addressed in this document, check out these resources:

- [**HelpHub**](https://wordpress.org/documentation/) — the encyclopedia of all things WordPress  
- [**WordPress Blog**](https://wordpress.org/news/) — latest updates and news  
- [**WordPress Planet**](https://planet.wordpress.org/) — news aggregator of WordPress-related blogs  
- [**Support Forums**](https://wordpress.org/support/forums/) — ask for help and contribute  
- [**WordPress IRC Channel**](https://make.wordpress.org/support/handbook/appendix/other-support-locations/introduction-to-irc/) — online chat community on [irc.libera.chat #wordpress](https://web.libera.chat/#wordpress)

---

## 🧩 Final Notes

- Found a bug or have ideas? Join us at the [Support Forums](https://wordpress.org/support/forums/).  
- Developers can use the [Plugin Developer Handbook](https://developer.wordpress.org/plugins/) to extend WordPress via the Plugin API.  
  > You shouldn’t modify core code directly.

---

## 💖 Share the Love

WordPress doesn’t have a multi-million dollar marketing campaign — it has *you*.  
If you enjoy WordPress, please consider:
- Telling a friend
- Setting it up for someone less technical
- Writing to authors or media who overlook WordPress

WordPress is the official continuation of **b2/cafèlog** by Michel V., continued by the [WordPress developers](https://wordpress.org/about/).  
If you’d like to support WordPress, consider [donating](https://wordpress.org/donate/).

---

## 📜 License

WordPress is free software, released under the terms of the **GNU General Public License (GPL)** version 2 or (at your option) any later version.  
See [`license.txt`](license.txt) for details.
