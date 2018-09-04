Add dependencies (as submodules)
--------------------------------

trivial...

Recreate loadlibrary
--------------------

Recreate WindowsDefenderTools
-----------------------------

### MPENGINE offsets

"IMPORTANT: The offsets contained in this project are specific to the 6/25/2018 32-bit mpengine.dll build, MD5=e95d3f9e90ba3ccd1a4b8d63cbd88d1b. If you are using a different version of mpengine.dll, you'll need to locate these offsets yourself. It's easiest to wait for Microsoft to publish mpengine.dll PDBs with symbols, but it can be done easily without them."
        
    Offsets are in the .map file generated during loadlibrary setup

### Left out parts

"Note that the included patches only contain my OutputDebugStringA hooking code. This will let you experiment with the engine and reproduce some of the demos I have shown. Implementing more advanced functionality demonstrated in my presentation is left as an exercise to the reader, eg: building a fuzzer, supporting format string-based output, dumping out arbitrary non-string buffers, hooking ExitProcess to understand when emulation is ending, or collecting coverage with a customized Lighthouse Pintool (https://github.com/gaasedelen/lighthouse)."
