# SpamAssassin syntax highlight for VS Code

Support for the SpamAssassing configuration file syntax in Visual Studio Code.

## Features

The following statements are supported:

- meta
- score
- required_score
- describe
- header
- uri
- bayes_auto_learn
- bayes_auto_learn_threshold_nonspam
- bayes_auto_learn_threshold_spam
- body
- clear_headers
- clear_originating_ip_headers
- clear_report_template
- clear_unsafe_report_template
- else
- endif
- full
- if
- ifplugin
- lang
- mimeheader
- priority
- rawbody
- replace_inter
- replace_rules
- replace_tag
- report
- report_contact
- report_safe
- required_score
- reuse
- tflags
- unsafe_report

The syntax also supports comments and correctly highlight regular expressions and perl in eval expressions.

# Known issues

Missing support for the following statements:

- add_header
- adsp_override
- askdns
- def_whitelist_from_dkim
- def_whitelist_from_rcvd
- def_whitelist_from_spf
- dns_local_ports_avoid
- freemail_domains
- ok_languages
- ok_locales
- originating_ip_headers
- redirector_pattern
- replace_post
- require_version
- test
- uridnsbl_skip_domain
- uridnssub
- urirhssub
- util_rb_2tld
- util_rb_3tld

## Release Notes

### 1.0.0

Initial release.
