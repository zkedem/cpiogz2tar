# cpiogz2tar
 A script to convert gzipped cpio archives to tar format.

## Usage
As simple as you'd expect:
`$ cpiogz2tar <archive you want to convert>`

## Notes
- This script unzips the cpio archive, unpacks it, and repacks it as a tar archive. At present, it does NOT create a .tar.gz archive!
	- This feature may be added in a future release.
- A Windows implementation (cpiogz2tar.cmd) may be provided in future for use with Win32 ports of gunzip and cpio

## License
cpiogz2tar is free software released under the GNU GPL, version 3.