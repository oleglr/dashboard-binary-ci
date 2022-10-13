## Fixed in GitHub - Need CPAN release
- Released to CPAN october 2022 ~[Time::Duration::Concise::Localize](https://metacpan.org/pod/Time::Duration::Concise::Localize) - fixed in [PR](https://github.com/binary-com/perl-Time-Duration-Concise-Localize/pull/22/files). Used in cpan-private~ 
- [Email::Stuffer::TestLinks](https://github.com/binary-com/perl-Email-Stuffer-TestLinks) is using `success` method [removed in Mojolicious 9](https://github.com/mojolicious/mojo/wiki/Upgrading#mojotransaction-success-removed) - ~~Need backward compatible fix (Deriv does not use Mojolicious 9)~~ Fixed in [PR](https://github.com/binary-com/perl-Email-Stuffer-TestLinks/pull/8/). Used in cpan-private. Another test output error.

## Has a fix
- [RateLimitations](https://metacpan.org/pod/RateLimitations) - depends on [Time::Duration::Concise::Localize](https://metacpan.org/pod/Time::Duration::Concise::Localize) (fixed above) and "Time::Duration::Concise" which seems not in CPAN
- Time::Duration::Concise::Localize] released to CPAN october 2022 ~[Date::Utility](https://metacpan.org/pod/Date::Utility) - depends on depends on [Time::Duration::Concise::Localize](https://metacpan.org/pod/Time::Duration::Concise::Localize) (fixed above)~

## Partially broken
- [Crypt::NamedKeys](https://metacpan.org/pod/Crypt::NamedKeys) is broken in CPAN and cpan-private **with recent perl interpreter*
