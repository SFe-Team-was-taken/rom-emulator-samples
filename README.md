# SFE ROM Sample Pack, Version 4.0

### What's new in this version?

None of the samples have been modified from the previous draft version, but the documentation is updated.

### What is this sample pack?

This SFE ROM sample pack contains ROM samples that are included in the SFe specification kit.

### What does this sample pack contain?

The sample pack contains 152 samples made to the same specifications as the original samples found in the Creative AWE sound card ROMs. These are useful for developing an SFE program, as SFE programs should implement a ROM emulator, and will be required to in the future. The total size of the sample pack is 1 megabyte. 

These samples share the same name, sample length, loop points, and format (44.1khz mono) as the ROM samples, and are drop in replacements for any soundfont that requires these samples. Because the sample properties are identical, even instruments and presets that use the sample/loop start/end offset parameters should work as-is without any further modifications required.

Please note that these samples are not intended to be used directly in SFE implementations. They might be unrealistic, horribly imbalanced or just unsuitable for use in a production environment. These samples are simply meant to be an example of samples to be used in a ROM emulator.

### How can I use these samples?

To start, find a copy of the 1MB AWE soundfont online, and then overwrite the samples with those from this pack. We are not allowed to redistribute the 1MB AWE soundfont in the SFE SDK, because it contains samples that do not belong to us. It is for the same reason that we do not distribute the SFE specification as a derivative of the legacy SF 2.04 specification.

We do not provide a version of the 1MB AWE soundfont default presets with the samples, because these samples are not intended to be used directly in SFE implementations. This is because they sound relatively unrealistic compared with the original Creative samples. It is also likely that the parameters used in the soundfont are copyrighted and not redistributable with open source software.

### Where do the samples come from?

The samples are derived from [The Fixed Jummbox Soundfont](https://stgiga.itch.io/jummboxsoundfont) by stgiga. They developed it with collaboration by Micasddsa4095, NPC, Zandro Reveille, TheFatMan, drunkenjesus, little-scale, Retro Player, William B. Santos, shaktool, and JummBus. Some samples are taken from the YMF262, YM3812, YM2612 and YM2413 FM synthesiser ICs.

The license of the original soundfont is [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), so please respect this license when using this sample pack.

### How do I give feedback?

You can give feedback using the contacts listed in section 2.1 of the SFE specification. Make sure that you have the latest version of the specification.

When using the sample pack for SFE program development, also use the latest version. Earlier versions may not be as close to the original samples.

### What work needs to be done?

In addition to simply improving the basic 152-sample 1MB sample pack, we thought that we may need to make more sample packs that correspond to the ROM samples of later sound cards, but I've found pictures of the SB Live! cards online and they do not include an EMU8011 ROM chip. Documentation also suggests that they discontinued the use of ROM samples because they were able to use system memory instead. Therefore, for now let's assume that the only type of ROM that we need to emulate is the AWE one.

* * *

Copyright 2024-2025 sylvia-leaf.

This document is licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/).
