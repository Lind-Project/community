# Scope

The Lind Project develops techniques, specifications, and software for safely executing untrusted POSIX applications inside a single, unprivileged host process, without kernel modifications or elevated privileges, while supporting multiple host environments and targeting multiple isolation backends.

Lind's scope encompasses:

* Specifying and implementing the interfaces between sandboxed applications ("cages"), interposition layers ("grates"), and the Lind runtime, including system call routing and the POSIX-compatible interface exposed to cages.

* Specifying and implementing isolation backends for Lind, such as WebAssembly-based runtimes and hardware-assisted memory protection.

* Defining practices for building, porting, and evaluating applications and libraries that run under Lind, including benchmarks and test suites.

This Scope establishes the bounds of each Contributor's and Licensee's patent commitment under the [Community Specification License 1.0](COMMUNITY_SPECIFICATION_LICENSE.md).

Any changes of Scope are not retroactive.
