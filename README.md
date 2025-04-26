Lisst of hidden, forgotten, or sensitive file extensions and paths** that can lead to information disclosure, misconfigurations, or default admin access if exposed. Great for fuzzing or manual recon on `/admin` or other sensitive directories.


## 🧩 Forgotten Extensions & Backup Files

```
.bak
.old
.orig
.backup
.save
.swp
.swo
.tmp
~ (e.g., index.php~)
.inc
.git
.env
.DS_Store
.ftpconfig
.idea/
.vscode/
Thumbs.db
.npmrc
.yarnrc
composer.lock
package-lock.json
```

---

## 🔐 Sensitive or Default Pages (Common under `/admin`, `/config`, etc.)

```
admin.php
admin.html
index.php.bak
config.php
config.php.old
config.inc.php
phpinfo.php
test.php
debug.php
dev.php
setup.php
install.php
upgrade.php
web.config
app.config
robots.txt
crossdomain.xml
sitemap.xml
```

---

## 📦 CMS / Framework Specific

### WordPress
```
/wp-admin/
/wp-login.php
/xmlrpc.php
/wp-config.php.bak
/wp-content/debug.log
```

### Laravel
```
/.env
/storage/logs/laravel.log
/vendor/
/debugbar
```

### Django
```
/admin/
/static/
/media/
/settings.py
```

### Node.js / Express
```
/debug/
/config.js
/.env
/routes.js
/app.js
```

### Drupal
```
/user/login
/update.php
/install.php
```

---

## 🛠️ Dev Tools / Misconfigured Stuff

```
/debug/
/dev/
/staging/
/test/
/beta/
/cgi-bin/
/server-status
/server-info
/.htaccess
/.htpasswd
/.git/config
/.svn/entries
```
