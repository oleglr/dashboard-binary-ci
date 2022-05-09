## Fixed in GitHub - Need CPAN release
- [Time::Duration::Concise::Localize](https://metacpan.org/pod/Time::Duration::Concise::Localize) - fixed in [PR](https://github.com/binary-com/perl-Time-Duration-Concise-Localize/pull/22/files). Used in cpan-private

## Has a fix
- [RateLimitations](https://metacpan.org/pod/RateLimitations) - depends on [Time::Duration::Concise::Localize](https://metacpan.org/pod/Time::Duration::Concise::Localize) (fixed above) and "Time::Duration::Concise" which seems not in CPAN 
- [Date::Utility](https://metacpan.org/pod/Date::Utility) - depends on depends on [Time::Duration::Concise::Localize](https://metacpan.org/pod/Time::Duration::Concise::Localize) (fixed above)

## Partially broken
- [Crypt::NamedKeys](https://metacpan.org/pod/Crypt::NamedKeys) is broken in CPAN and cpan-private **with recent perl interpreter*
