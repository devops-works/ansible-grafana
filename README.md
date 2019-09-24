ansible-grafana role
====================

[![Build Status](https://travis-ci.org/devops-works/ansible-grafana.svg?branch=master)](https://travis-ci.org/devops-works/ansible-grafana)

Installs [grafana](http://grafana.org/) on ubuntu 16.04 and up.

Variables are defined in `defaults/main.yml`

Sections `session`, `analytics`, `auth.proxy`, `log`, and `dashboards.json` are not templated for now.

Michel Blanc <mb@mbnet.fr>
