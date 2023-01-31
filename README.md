# gnupg public key

This repo contains the GnuPG public key associated with this account and information on ways to add it to your keychain.

## Key details
``` bash
$ gpg --list-keys --keyid-format LONG 121760096+biot-2131@users.noreply.github.com

pub   rsa4096/1D55F46A1B5331BA 2023-01-02 [SC]
      B39CBE4418F72D5665399D9D1D55F46A1B5331BA
uid                 [ultimate] biot-2131 <121760096+biot-2131@users.noreply.github.com>
sub   rsa4096/A2AAB8A9C02E065E 2023-01-02 [E]
```

## Keyserver
``` bash
$ gpg --keyserver http://keyserver.ubuntu.com --search-key B39CBE4418F72D5665399D9D1D55F46A1B5331BA

$ gpg --keyserver http://keyserver.ubuntu.com --recv-keys B39CBE4418F72D5665399D9D1D55F46A1B5331BA

$ gpg --list-keys --keyid-format LONG 121760096+biot-2131@users.noreply.
```

## Download & import key 
``` bash
$ wget https://raw.githubusercontent.com/biot-2131/gpg_public_key/main/121760096+biot-2131@users.noreply.github.com_public.asc

$ gpg --import 121760096+biot-2131@users.noreply.github.com_public.asc

$ gpg --list-keys --keyid-format LONG 121760096+biot-2131@users.noreply.
```

## Cut & paste key
```bash 
-----BEGIN PGP PUBLIC KEY BLOCK-----

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
fVQB5l5yIPkkOl11Lz8YNwlSLZ8=
=978V
-----END PGP PUBLIC KEY BLOCK-----
```