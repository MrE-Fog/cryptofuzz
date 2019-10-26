# Cryptofuzz - Differential cryptography fuzzing

## Documentation

Documentation on how to implement modules and use Cryptofuzz will follow.

## Hall of Fame

- OpenSSL: [ARIA GCM ciphers memory leak after EVP_CTRL_AEAD_SET_IVLEN](https://github.com/openssl/openssl/issues/8567)
- OpenSSL: [HMAC with SHAKE128 via EVP interface crashes on EVP_DigestSignUpdate](https://github.com/openssl/openssl/issues/8563)
- OpenSSL: [BLAKE2b_Update can pass NULL to memcpy (undefined behavior)](https://github.com/openssl/openssl/issues/8576)
- LibreSSL: [EVP_aes_128_cbc_hmac_sha1, EVP_aes_256_cbc_hmac_sha1 decrypt OOB read/crash/invalid result](https://cvsweb.openbsd.org/cgi-bin/cvsweb/src/lib/libcrypto/evp/e_aes_cbc_hmac_sha1.c?rev=1.15&content-type=text/x-cvsweb-markup)
- OpenSSL: [CHACHA20_POLY1305 different results for chunked/non-chunked updating](https://github.com/openssl/openssl/issues/8675)
- OpenSSL: [OpenSSL 1.0.2: BIO_read + *_WRAP ciphers copy to uninitialized pointer](https://github.com/openssl/openssl/issues/8688)
- BoringSSL: [AEAD AES GCM SIV NULL pointer dereference/OOB read](https://boringssl-review.googlesource.com/c/boringssl/+/35545)
- LibreSSL: [BIO_read can report more bytes written than buffer can hold](https://cvsweb.openbsd.org/src/lib/libcrypto/bio/bio_lib.c?rev=1.29&content-type=text/x-cvsweb-markup)
- LibreSSL: [Use-after-free/bad free after EVP_CIPHER_CTX_copy](https://cvsweb.openbsd.org/src/lib/libcrypto/evp/evp_enc.c?rev=1.41&content-type=text/x-cvsweb-markup)
- BoringSSL: [Use-after-free/bad free after EVP_CIPHER_CTX_copy](https://boringssl.googlesource.com/boringssl/+/65dc45cb57c7c6900a0657f6ee5c00fce9d366f5)
- LibreSSL: [GOST HMAC uses and outputs uninitialized memory](https://cvsweb.openbsd.org/src/lib/libcrypto/evp/digest.c?rev=1.31&content-type=text/x-cvsweb-markup)
- OpenSSL: [Overlong tag buffer leaves memory uninitialized in CCM mode](https://github.com/openssl/openssl/pull/8810)
- OpenSSL: [Buffer write overflow when passing large RC5 key](https://github.com/openssl/openssl/pull/8834)
- OpenSSL: [Hang after particular sequence of operations](https://github.com/openssl/openssl/issues/8827)
- LibreSSL: [Overlong tag buffer leaves memory uninitialized in CCM mode](https://cvsweb.openbsd.org/src/lib/libcrypto/modes/ccm128.c?rev=1.5&content-type=text/x-cvsweb-markup)
- LibreSSL: [AES GCM context copy crash](https://cvsweb.openbsd.org/src/lib/libcrypto/evp/e_aes.c?rev=1.38&content-type=text/x-cvsweb-markup)
- LibreSSL: [Streebog wrong output](https://cvsweb.openbsd.org/cgi-bin/cvsweb/src/lib/libcrypto/gost/streebog.c?rev=1.6&content-type=text/x-cvsweb-markup)
- OpenSSL: [EVP_EncryptUpdate, EVP_EncryptFinal_ex branching on uninitialized memory](https://github.com/openssl/openssl/pull/8874)
- libgcrypt: [Invalid output of MD4, MD5, RIPEMD160](https://lists.gnupg.org/pipermail/gcrypt-devel/2019-May/004712.html)
- OpenSSL: RC5 signed integer overflow, TBA
- LibreSSL: [AES CCM context copy crash](https://cvsweb.openbsd.org/src/lib/libcrypto/evp/e_aes.c?rev=1.39&content-type=text/x-cvsweb-markup)
- LibreSSL: [DES EDE3 CFB1 leaves output uninitialized](https://cvsweb.openbsd.org/src/lib/libcrypto/evp/e_des3.c?rev=1.20&content-type=text/x-cvsweb-markup)
- Crypto++: [Scrypt crash with blocksize 0](https://github.com/weidai11/cryptopp/commit/e0b60439bf63b02ed93bc2c5b4ed15125fd6f278)
- EverCrypt: Illegal instruction exception on non-AVX CPUs
- OpenSSL: [OpenSSL 1.0.2: RC4 OOB read](https://github.com/openssl/openssl/issues/8972)
- OpenSSL: [OpenSSL 1.0.2: Branch on uninitialized memory in EVP_CIPHER_CTX_copy](https://github.com/openssl/openssl/issues/8980)
- Crypto++: [PBKDF1 OOB read](https://github.com/weidai11/cryptopp/issues/874)
- NSS: [MD2 invalid output](https://bugzilla.mozilla.org/show_bug.cgi?id=1575923)
- Botan: [CAST5_CBC invalid output](https://github.com/randombit/botan/issues/2081)
- Botan: [Streebog invalid output](https://github.com/randombit/botan/issues/2082)
- Botan: [PBKDF2 hang (very long loop) if iterations == 0](https://github.com/randombit/botan/issues/2088)
- NSS: [HKDF SHA1 stack buffer overflow, CVE-2019-11759](https://hg.mozilla.org/projects/nss/rev/c0913ad7a5609751a8dfc37ae2e0a7a0cd6a42dd)
- NSS: [RC2 CBC OOB read with undersized IV](https://hg.mozilla.org/projects/nss/rev/53d92a32408049038f450aa747b0030607988230)
- NSS: [SEED_CBC encryption out-of-bounds write](https://hg.mozilla.org/projects/nss/rev/7580a5a212c78ab21fc4878330dd7872c3b530b8)
- NSS: [CKM_AES_GCM succeeds with invalid tag sizes, risk of memory corruption](https://hg.mozilla.org/projects/nss/rev/4e3971fd992c0513d0696048c64b7230e5b6039b)
- NSS: [PBKDF2 memory leak if key size > 256](https://bugzilla.mozilla.org/show_bug.cgi?id=1591363)
