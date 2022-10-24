AUDIO PROCESSING REPOSITORY FOR AUDIO-VISUAL-PROCESSING COURSE OF 2022/2023
============================================================================

Focused on Speech Detection through diverse strategies:
-------------------------------------------------------
* How?    
    - Frequency Analysis
    - Power Analysis
    - Zero Cross Rate
    - Cepstrum 
    - Finite State System for Silence Detection
    - Computing diverse properties from input files
    - Comparation of results with Database of other year subjects

Programming Skills
----------------------
* Basically all with C

    - File System manmagement (open, seek, close ...)
    - Pointers 
    - Makefile
    - Bash
    - Git
    - Structs
    - "Oriented Programming" with C
    - Dynamic memory allocation (malloc, free)
    - Meson builds
    - Ninja
    - Audacity export files and previous analysis
    - docopt

    and more


**P1**
----

Basically an introduction to audio processing.
Given an audio file and taking into account the WAVE structure.

| Canonical WAVE FORMAT (each cell is 4 bytes) |a|a |a |    a          |
|------------------------------------------------------------------|
|  ChunkID    |   ChunkSize  | Format | SubchunkID | SubchunkSize|        
| AudioFormat | NumChannels | SampleRate| ByteRate | BlockALign |
| BitsPerSample| SubChunk21D | Subchunk2 Size| DATA|DATA |
|    DATA |DATA| DATA| DATA | DATA|


