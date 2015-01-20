
[size=4][color=red][b]Restrict Emails on Registration[/b][/color][/size]

Version: 1.1 Date 2015-01-19
Compatibility: SMF 2.0.7-2.0.9 (tested)


[hr]

This modification gives the admin the chance to restrict emails allowed to be used for registration. It is sometimes useful to limit the emails used to register to stop spam, create a semi-private forum more easily, or to stop people from signing up with problematic email providers.

You will be able to create email rules of one of two types: blacklists or whitelists. Your lists can be made up of any valid string that can be in an email address. This allows you to do more than just forbid email addresses from a specific domain (eg, '@gmail.com'), but you can ban all email addresses that contain a certain string (eg, 'john.smith') as well.

This mod was forked from [url=http://custom.simplemachines.org/mods/index.php?mod=1493]Restrict Email Providers on Registration[/url]

[hr]

[color=red][b]How do you activate it?[/b][/color]

Admin -> Package Manager -> Modification Packages -> Install Mod "Restrict Email Providers on Registration"

Later days
Defron

[hr]

[color=red][b]Changelog[/b][/color]

Version: 1.1
Release Date: 2015-01-19

[list]
[li]Made comparison case-insensitive.[/li]
[/list]

Version: 1.0
Release Date: 2015-01-18

[list]
[li]Initial fork from [url=http://custom.simplemachines.org/mods/index.php?mod=1493]Restrict Email Providers on Registration[/url][/li]
[li]Switched to strpos() to simplify codebase[/li]
[li]Allow arbitrary string matching instead of just email providers[/li]
[/list]