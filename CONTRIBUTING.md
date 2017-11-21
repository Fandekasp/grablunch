# Local setup

## Install packages

    $ flutter packages get

## Generate locales

    $ flutter pub pub run intl_translation:extract_to_arb --output-dir=lib/l10n lib/localization.dart
    $ flutter pub pub run intl_translation:generate_from_arb --output-dir=lib/l10n --no-use-deferred-loading lib/localization.dart lib/l10n/intl_*.arb
