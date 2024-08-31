# SFe ROM Sample Pack, Version 4.00.5

### What's new in this version?

This is the first version of this sample pack, but we will list any differences from previous versions here.

### What is this sample pack?

This SFe ROM sample pack is a preview of the ROM samples that will be included in the SFe SDK, version 4.00.

The SDK is not currently available, but we are working on it and it will release once the final version of the SFe specification, version 4.00, becomes available. Right now, we are targeting the end of 2026, but we can't guarantee it. We will release it when it's done.

### What does this sample pack contain?

The sample pack contains 152 samples made to the same specifications as the original samples found in the Creative AWE sound card ROMs. These are useful for developing an SFe program, as a ROM emulator is required for all SFe programs. The total size of the sample pack is 1 megabyte. 

These samples share the same name, sample length, loop points, and format (44.1khz mono) as the ROM samples, and are drop in replacements for any soundfont that requires these samples. Because the sample properties are identical, even instruments and presets that use the sample/loop start/end offset parameters should work as-is without any further modifications required.

Please note that these samples are not intended to be used directly in SFe implementations. They might be unrealistic, horribly imbalanced or just unsuitable for use in a production environment. These samples are simply meant to be an example of samples to be used in a ROM emulator.

### How can I use these samples?

To start, find a copy of the 1MB AWE soundfont online, and then overwrite the samples with those from this pack. We are not allowed to redistribute the 1MB AWE soundfont in the SFe SDK, because it contains samples that do not belong to us. It is for the same reason that we do not distribute the SFe specification as a derivative of the legacy SF 2.04 specification.

We do not provide a version of the 1MB AWE soundfont default presets with the samples, because these samples are not intended to be used directly in SFe implementations. This is because they sound relatively unrealistic compared with the original Creative samples. It is also likely that the parameters used in the soundfont are copyrighted and not redistributable with open source software.

### What will the full SDK contain?

The full SDK will contain not only this sample pack, but also compilers/decompilers to/from SFZ, converters to/from SF2/SF3, an SF2/SF3/SFe repair program and SFe test files to load in your programs.

The SDK will also contain the source code for all these programs. All source code will be released under GPL-compatible open source licenses, so you can reuse any part of the sample programs in your software.

The programming language is not confirmed yet, but it could be anything. We haven't decided yet. For what it's worth, we might write the programs in Visual Basic. The plan is to eventually rewrite everything in C or C++.

Talking about full SFe editors or players, we plan on working with developers of the software to add SFe support. We want users to create SFe files knowing that they will work with the leading FOSS soundfont programs, rather than any implementation that we would make. Thus, we may not provide such facilities in the SDK.

The SFe SDK will be designed specifically for developers of programs that use the SFe format, rather than developers of SFe banks themselves. Future SFe file editors from the leading soundfont program developers should be suitable for such use.

### Where do the samples come from?

The samples are derived from [The Fixed Jummbox Soundfont](https://stgiga.itch.io/jummboxsoundfont) by stgiga. They developed it with collaboration by Micasddsa4095, NPC, Zandro Reveille, TheFatMan, drunkenjesus, little-scale, Retro Player, William B. Santos, shaktool, and JummBus. Some samples are taken from the YMF262, YM3812, YM2612 and YM2413 FM synthesiser ICs.

The license of the original soundfont is [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), so please respect this license when using this sample pack.

### How do I give feedback?

You can give feedback using the contacts listed in section 0.3 of the SFe specification. Make sure that you have the latest version of the specification.

When using the sample pack for SFe program development, also use the latest version. Earlier versions may not be as close to the original samples.

### What work needs to be done?

In addition to simply improving the basic 152-sample 1MB sample pack, we might need to make more sample packs that correspond to the ROM samples of later sound cards.

* * *

Copyright 2024 sleaf.

This document is licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/).
