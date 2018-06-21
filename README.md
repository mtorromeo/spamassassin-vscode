# SpamAssassin syntax highlight for VS Code

Support for the SpamAssassing configuration file syntax in Visual Studio Code.

## Features

Highlights comments, meta, score, describe, header and uri definitions.

It also supports regexp highlight where applicable.

# Known issues

Missing support for the following statements:

- add_header
- adsp_override
- askdns
- bayes_auto_learn
- bayes_auto_learn_threshold_nonspam
- bayes_auto_learn_threshold_spam
- body
- clear_headers
- clear_originating_ip_headers
- clear_report_template
- clear_unsafe_report_template
- def_whitelist_from_dkim
- def_whitelist_from_rcvd
- def_whitelist_from_spf
- dns_local_ports_avoid
- else
- endif
- freemail_domains
- full
- if
- ifplugin
- lang
- mimeheader
- ok_languages
- ok_locales
- originating_ip_headers
- priority
- rawbody
- redirector_pattern
- replace_inter
- replace_post
- replace_rules
- replace_tag
- report
- report_contact
- report_safe
- required_score
- require_version
- reuse
- test
- tflags
- unsafe_report
- uridnsbl_skip_domain
- uridnssub
- urirhssub
- util_rb_2tld
- util_rb_3tld

## Release Notes

### 1.0.0

Initial release.
