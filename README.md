# piCrypt
piCrypt is a CLI encryption/decryption program written in Python3 for linux.
It requires the linux package python-crypto.

	Useage: piCrypt [options] [arguments]

	Options:

        -h, --help: Shows this help screen.
        -e, --encrypt: Sets program to encrypt files.
        -d, --decrypt: Sets program to decrypt files.
        -r, --read: Prints output of file to screen instead of
                writing to file (to be used -d, --decrypt).

        Arguments:
        Arguments passed are files to be encrypted or decrypted.
        If directories are passed as arguments without the recursive option,
        all files within specified directory will be encrypted or decrypted.
        If directories are passed as arguments with the recursive option,
        piCrypt will traverse all contained files and directories and
        encrypt or decrypt all files.
