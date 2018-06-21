# Change Log
All notable changes to the "spamassassin" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [Unreleased]

### Added
- Implemented support for the following statements:
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

### Fixed
- Comments at the end of a line are now correctly highlighted

## 1.0.0
- Initial release

[Unreleased]: https://github.com/mtorromeo/spamassassin-vscode/compare/v1.0.0...HEAD
