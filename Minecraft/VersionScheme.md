## The following is the version scheme used in all of my Minecraft modpack projects:


*(if you are familiar with version schemes, you can skip to the "fourth number" marked in bold).*

My modpack projects use a variant of the basic standard versioning scheme. There are four variables in the format X.X.X-X.

The first number represents a major version/ change and is not backwards compatible. Game breaking changes happen between these, and thus world saves should never move between major versions.

The second number is a content update, and is backwards compatible. This involves the addition or removal of content, and can sometimes mean items disappearing from your world (but they won't technically break).

The third number is the patch version. These contain bug fixes and are also backwards compatible.

The **fourth number** after the dash corresponds to a server pack version. Server pack versions are tracked separately, and the part that needs to match is the fourth number after the dash on both versions (E.g client version 12.4.6-17 and server version 11.20.3-17 would be compatible). The fourth number of both client and server MUST match.

Version numbers of files are tracked separately for Alpha, Beta, and Release files. As a general rule, worlds may or may not be backwards compatible between Beta and Release files. Beta files are for testing, should not be used by regular players, and updating between them and Release files is done at your own risk.
Exceptions are stated in the changelog, and It's not my problem if you don't read it before updating. Note that only Release versions have corresponding server files.

*(The following info is only important to devs or play-testers).*

Beta version schemes for Betas that come out in between releases works as follows: A Beta version is released to test a future Release. The file will maintain the version of the next stable Release plus a Beta version tagged on at the end. E.g if the last Release version is 2.6.4, and a Beta version is released to test features for the eventual Release of lets say 2.7.0, the Beta will have version 2.7.0_B1.0.0 (First Beta of version 2.7, incremented.). If the eventual release version after any Betas does not contain changes, then it will state so in the changelog that it is a Beta rebrand. If you are already on the Beta, you need not update. Stable Betas which contain no differences between it and the eventual Release file are simply rebranded as a Release for regular players.  
