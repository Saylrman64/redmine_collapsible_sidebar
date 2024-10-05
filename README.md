# Collapsible Stateful Sidebar

[![Run RuboCop](https://github.com/AlphaNodes/redmine_collapsible_sidebar/workflows/Run%20Linters/badge.svg)](https://github.com/AlphaNodes/redmine_collapsible_sidebar/actions/workflows/linters.yml)

## Features

- collapsable sidebar
- Using local storage to remember status of the sidebar for each page

Solution is based on <https://www.redmine.org/issues/21808#note-27>. If this is part of Redmine, this plugin will be deprecated.

## Requirements

- Redmine version >= 5.0
- Redmine Plugin: [additionals](https://github.com/alphanodes/additionals) - used for FontAwesome support
- Ruby version >= 3.0

## Installation

```shell
cd $REDMINE_ROOT
git clone https://github.com/alphanodes/redmine_collapsible_sidebar.git plugins/
git clone git://github.com/alphanodes/additionals.git plugins/additionals
bundle config set --local without 'development test'
bundle install
```

Restart your application server after installation.

## Uninstall

Uninstall `redmine_collapsible_sidebar` plugin.

```shell
cd $REDMINE_ROOT
rm -rf plugins/redmine_collapsible_sidebar public/plugin_assets/redmine_collapsible_sidebar
```

Restart Redmine (application server)

## License

This plugin is licensed under the terms of GNU/GPL v2.
See [LICENSE](LICENSE) for details.

## Redmine Copyright

The redmine_collapsible_sidebar is a plugin extension for Redmine Project Management Software, whose Copyright follows.
Copyright (C) 2006-  Jean-Philippe Lang

Redmine is a flexible project management web application written using Ruby on Rails framework.
More details can be found in the doc directory or on the official website <http://www.redmine.org>

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program; if not, write to the Free Software Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.
