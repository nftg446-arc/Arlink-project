# Arlink-project
Project Name: my-first-app
Branch: main
Install Command: npm ci  # or yarn install
Build Command: npm run build  # or yarn build
Output Directory: dist  # or build
pam_yubico NEWS -- History of user-visible changes.             -*- outline -*-

* Version 2.28 (unreleased)

* Version 2.27 (released 2021-04-09)

** Add always_prompt configuration option.

** Add client certificate support for ldap.

** Add starttls support for ldap.

** Add ldap_bind_as_user support.

** Parsing, cleanliness and string fixes.

** Documentation and spelling fixes.

* Version 2.26 (released 2018-04-20)

** Make sure to close authfile (CVE-2018-9275).

** Fix compiler warnings.

** Open file descriptors with O_CLOEXEC.

** Use mkostemp() instead of mkstemp().

* Version 2.25 (released 2018-03-27)