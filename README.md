WP-Allowed-Hosts
================

WordPress plugin that allows you to specify a regular expression to be checked against the `http_request_host_is_external` filter. Hosts that start with 192.* or 10.* are checked against the allowed hosts based on a new security update WordPress introduced in 3.5.2 (https://github.com/WordPress/WordPress/commit/1ec392175ce5f0320072e7b195a8d091bccddefb). Unfortunately there is no setting available to say which hosts are allowed. :( This plugin gives you that option. The domains entered are checked using regular expressions. This is most helpful when trying to import media content from one wordpress instance to another from within an internal network.
