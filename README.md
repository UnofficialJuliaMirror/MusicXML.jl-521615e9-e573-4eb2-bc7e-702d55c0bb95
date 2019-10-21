# MusicXML

[![Dev](https://img.shields.io/badge/docs-dev-blue.svg)](https://aminya.github.io/MusicXML.jl/dev)
[![Build Status](https://travis-ci.com/aminya/MusicXML.jl.svg?branch=master)](https://travis-ci.com/aminya/MusicXML.jl)
[![Build Status](https://ci.appveyor.com/api/projects/status/github/aminya/MusicXML.jl?svg=true)](https://ci.appveyor.com/project/aminya/MusicXML-jl)
[![Coverage](https://codecov.io/gh//.jl/branch/master/graph/badge.svg)](https://codecov.io/gh//.jl)

Powerful MusicXML reading and writing package for Julia.

# Installation
```julia
] add https://github.com/aminya/MusicXML.jl
```
# Usage Example
```julia
using MusicXML
data = readmusicxml(joinpath(Pkg.dir("MusicXML"), "examples", "musescore.musicxml"))
```

# Documentation
[![Dev](https://img.shields.io/badge/docs-dev-blue.svg)](https://aminya.github.io/MusicXML.jl/dev)

# Types and Functions

You can use among these exported types and functions:

# I/O functions
```julia
readmusicxml, parsemusicxml
```

# Types:
```julia
MusicXML, Part, Measure, Note, Unpitched, Rest, Pitch, Attributes, Time, Transpose, Clef, Key, Partlist, Scorepart, Midiinstrument, Mididevice, Scoreinstrument
```

# Utilities
```julia
pitch2xml, xml2pitch
```

# XML utilities
```julia
findfirstcontent, findallcontent
```
