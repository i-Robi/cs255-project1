Sammy El Ghazzal - Sébastien Robaszkiewicz

Our script should be used as described by Lucas in his Piazza post.

Few remarks about the implementation

Dummy Database Entry (used to check the password, cf. 1.1.2 in the write-up): CXJTucBBuM/eQQV6v2B4SaVXn3Txsitydj2IUVCBEfqd5xuQ9ISZI7Am6/m5y1RDvwYp9BkXl3Mo3DMGeyT3kcJf7wNdcVb7dD6lS3cNg78k820mskPciOjZ1ZLGgLCClxHNdX9pW/Z1UMwE+88r94TNZpTaV2FWpTUr5uvcLL0=
It is associated with the value 0000

There are a lot of helper functions in the code. The crucial functions are:
- encryptString
- decryptString
as all the cryptographic aspects of the projects are in those two functions.
