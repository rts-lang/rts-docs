## Package Manager

RTS has a package manager that allows you to easily manage libraries 
and use different versions of the same package simultaneously.

Its main task is to maintain global storage for the user locally and 
provide the ability to create new packages and send them to the server. 
More detailed information about creating and managing packages can be 
found in the [Packages Section](https://realtime.su/packages).

The package manager only adheres to hot stable releases in the format:
`<package name>-<release date>.<revision>`. This way the package manager 
and the users can quickly understand which version is the latest.

The package name can only contain letters (a-z, A-Z), numbers (0-9) and 
hyphens (-), excluding the first character. The name must be at least two 
characters long.

The package manager focuses on supporting only modern and user-maintained code.