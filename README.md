# libvsl
VSL standard type library. The VSL standard library includes most functions for
a variety of systems including WASM which provides critical behaviors such as
the `Object` class along with the integer classes and classes used for memory
allocations.

VSL's standard type explicitly supports alongside POSIX:

 - Windows (win32)
 - WASM (wasm)

VSL's standard type also assumes any system that is not Windows or WASM to be
POSIX compliant unless stated otherwise.
