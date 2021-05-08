# apk-signer
apk-signer is a bash script progams which is help you to sign an apk in easy process by your legal documents.

## Example :~

```
ghosthub@localhost:/storage/internal$ bash apk-signer.sh

   [©]Powered By : Ghosthub

[+] Ok You Are In Root

[+] Ok zipalign Successfully Founded

[+] Ok Java Successfully Founded

  SSSS  S   SSSS S   S         S   SSSS  S   S

 S      S  S     SS  S        S S  S   S S  S

  SSS   S  S  SS S S S       S   S SSSS  SSS

     S  S  S   S S  SS       SSSSS S     S  S

 SSSS   S   SSSS S   S       S   S S     S   S

Enter ALIAS Name:babay

Enter keystore password:

Re-enter new password:

What is your first and last name?

  [Unknown]:  babaydas

What is the name of your organizational unit?

  [Unknown]:  technicalhub

What is the name of your organization?

  [Unknown]:  technicalhub

What is the name of your City or Locality?

  [Unknown]:  Kolkata

What is the name of your State or Province?

  [Unknown]:  WestBengal

What is the two-letter country code for this unit?

  [Unknown]:  91

Is CN=babaydas, OU=technicalhub, O=technicalhub, L=Kolkata, ST=WestBengal, C=91 correct?

  [no]:  yes

Generating 2,048 bit RSA key pair and self-signed certificate (SHA256withRSA) with a validity of 10,000 days

        for: CN=babaydas, OU=technicalhub, O=technicalhub, L=Kolkata, ST=WestBengal, C=91

[Storing release.jks]

Enter Your APP  : babay.apk

   [+]Zipaligning Your Apk Please Wait....

[+] Successfully Zipaligned ✔️

   [+]Verifying Your Zipaligned Apk Please Wait....

[+] Successfully Verified ✔️

Enter Your ALIAS Again :babay

   [+]Signing Your Apk Please Wait ....

source:

        /storage/internal

zipalign location: PATH

        /usr/bin/zipalign

keystore:

Please enter the keystore password for config [0] 'release.jks':

Please enter the key password for config [0] alias 'babay' and keystore 'release.jks':

        [0] f722c45f /storage/internal/release.jks (RELEASE_CUSTOM)

01. my-aligned.apk

        SIGN

        file: /storage/internal/my-aligned.apk (0.01 MiB)

        checksum: dd19038c466ecb5edc418af58fdc815357865c97ed8dd13911c396303c71fed7 (sha256)

        - zipalign success

        - sign success

                Signed

        VERIFY

        file: /storage/internal/output/my-aligned-aligned-signed.apk (0.02 MiB)

        checksum: b90de4d739b6afe0b22ec75450f2d9d4a566ddfea40e10080c73e38e51eab418 (sha256)

        - zipalign verified

        - signature verified [v1, v2, v3]

                Subject: CN=babaydas, OU=technicalhub, O=technicalhub, L=Kolkata, ST=WestBengal, C=91

                SHA256: 6816f58af738a8b851e9cc6ba7b53220b3f39b43b92396316cf5bdf253181836 / SHA256withRSA

                SHA1: 14352905f92d3874bb8c1ef515c0925795e2a161

                Issuer: CN=babaydas, OU=technicalhub, O=technicalhub, L=Kolkata, ST=WestBengal, C=91

                Public Key SHA256: 0b7e2d4fa06787b8ccf2fc7fe173edec9c3c61272b978e590d75c72a042fcb52

                Public Key SHA1: f31d9add0e64faad63a3e3c0858ca665b3b3281b

                Public Key Algo: RSA 2048

                Issue Date: Sat May 08 07:57:12 UTC 2021

                Expires: Wed Sep 23 07:57:12 UTC 2048

delete temp file output/my-aligned-aligned.apk

[Sat May 08 07:57:44 UTC 2021][v1.2.1]

Successfully processed 1 APKs and 0 errors in 3.04 seconds.

[+] Sign Completed ✔️

   [+]Verifying The Apk Please Wait ...

source:

        /storage/internal/output

zipalign location: PATH

        /usr/bin/zipalign

01. my-aligned-aligned-signed.apk

        VERIFY

        file: /storage/internal/output/my-aligned-aligned-signed.apk (0.02 MiB)

        checksum: b90de4d739b6afe0b22ec75450f2d9d4a566ddfea40e10080c73e38e51eab418 (sha256)

        - zipalign verified

        - signature verified [v1, v2, v3]

                Subject: CN=babaydas, OU=technicalhub, O=technicalhub, L=Kolkata, ST=WestBengal, C=91

                SHA256: 6816f58af738a8b851e9cc6ba7b53220b3f39b43b92396316cf5bdf253181836 / SHA256withRSA

                Expires: Wed Sep 23 07:57:12 UTC 2048

[Sat May 08 07:57:46 UTC 2021][v1.2.1]

Successfully processed 1 APKs and 0 errors in 0.92 seconds.

[+] Verification Completed ✔️

   [+]Backup Apk Please Wait ...

   [+]All Process Are Done ✔️, Check Output Dir & Backup Dir

```

## Made By : Ghosthub
