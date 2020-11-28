Example of a build test of a library via Github Actions. Here it builds [Perl5](https://github.com/perl/perl5) on Windows on WSLv1 (Ubuntu 20.04, both case-sensitive and case-insensitive mounts).

For that I use a Github Action [setup-wsl](https://github.com/Vampire/setup-wsl).

This example is for demonstrating [Perl5](https://github.com/perl/perl5) build bugs [perl5#18252](https://github.com/Perl/perl5/issues/18252) and [perl5#18254](https://github.com/Perl/perl5/issues/18254) (proposal of such a build configuration is in [perl5#18323](https://github.com/Perl/perl5/issues/18323)).
