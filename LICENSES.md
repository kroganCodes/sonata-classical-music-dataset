# SONATA Licensing, Attribution, and Redistribution Notice

**Dataset authors:** Aryan Rahman Mugdha and Saadman Bin Jashim

**Dataset:** SONATA (Augmented MAESTRO)

This file records the source-license information reviewed for the SONATA project. It is an attribution and rights notice, not a grant of rights over third-party recordings or MIDI files. SONATA is a derived compilation, and each source component remains subject to its own terms.

## Important distribution status

The complete SONATA corpus must not be represented as a single blanket open-source or Creative Commons release unless the maintainers have verified redistribution permission for every included file. The source materials have different rights statuses. In particular, the public-domain status of a historical composition does not automatically make a particular recording, MIDI sequence, or transcription free to redistribute.

For a public mirror such as Hugging Face, use one of these safer approaches:

1. Upload only files for which redistribution rights are documented.
2. Obtain written permission from the relevant dataset or sequence rightsholders before uploading the complete derived corpus.
3. Publish a metadata-only version and provide download instructions that point users to the original sources.

## Source-by-source status

### Google Magenta MAESTRO v3.0.0

- **Stated license:** Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0).
- **Official source:** https://magenta.tensorflow.org/datasets/maestro
- **Required practice:** retain attribution, link the license, identify modifications, and do not use the material commercially. Adapted material must be shared under compatible ShareAlike terms.
- **Citation:** Curtis Hawthorne et al., “Enabling Factorized Piano Music Modeling and Generation with the MAESTRO Dataset,” ICLR 2019.

### ASAP

- **Project cited in SONATA reports:** Foscarin et al., “ASAP: a dataset of aligned scores and piano performances,” ISMIR 2020.
- **Source identified during review:** the reports do not include a license notice for the exact ASAP files incorporated into SONATA, and the upstream repository/license could not be verified from the project materials available here.
- **Redistribution status:** **Unverified. Do not redistribute these files publicly until the exact upstream license or written permission is confirmed.**
- **Citation:** Foscarin et al., “ASAP: a dataset of aligned scores and piano performances,” ISMIR 2020.

### ADL Piano MIDI

- **Project page:** https://github.com/lucasnfe/adl-piano-midi
- **Citation:** Lucas N. Ferreira, Levi H. S. Lelis, and Jim Whitehead, “Computer-Generated Music for Tabletop Role-Playing Games,” AIIDE 2020.
- **Important rights note:** the ADL README describes a collection assembled from the Lakh MIDI Dataset and additional MIDI files scraped from publicly available internet sources. The ADL project page does not provide one blanket redistribution license for all files in that combined collection.
- **Underlying Lakh MIDI license:** the Lakh MIDI Dataset states CC BY 4.0 and requests attribution to Colin Raffel and his thesis: https://colinraffel.com/projects/lmd/
- **Redistribution status:** Lakh-derived files may have CC BY 4.0 terms, but the additional scraped ADL files require file-level/source-level verification. Do not assume the entire ADL collection is CC BY 4.0.

### Classical MIDI Archive

- **Website:** https://www.classicalmidi.co.uk/
- **Rights note:** the site states that all MIDI pieces are not automatically free of copyright, asks users to contact the relevant sequencer for non-commercial use, and grants permission for the webmaster’s own sequences only when due credit and a link back to the site are provided.
- **Redistribution status:** **Restricted / not blanket-open.** The SONATA team must obtain permission for redistribution of each included sequence, or remove those files from a public mirror.
- **Composition status:** a composition may be public domain while a particular MIDI arrangement or recording is still protected.

## SONATA-authored material

The SONATA authors created the balancing, organization, metadata, processing, quality-control documentation, and derived annotations described in the reports. Those project contributions are attributed to **Aryan Rahman Mugdha and Saadman Bin Jashim**. They do not override or replace the rights of the upstream source owners.

The reports and metadata may be shared with attribution, but the audio and MIDI files must follow the most restrictive applicable upstream terms. A platform's dataset license field must not be used to imply that the maintainers own or relicense third-party content.

## Required attribution block

When permitted to redistribute a particular source component, retain the relevant source credit and add:

> SONATA (Augmented MAESTRO), by Aryan Rahman Mugdha and Saadman Bin Jashim. SONATA is a balanced derived compilation and processing of material from MAESTRO, ASAP, ADL Piano MIDI, and Classical MIDI Archive sources. See the source-specific rights notices in `LICENSES.md`.

## Official references reviewed

- MAESTRO: https://magenta.tensorflow.org/datasets/maestro
- CC BY-NC-SA 4.0 deed: https://creativecommons.org/licenses/by-nc-sa/4.0/
- Lakh MIDI Dataset: https://colinraffel.com/projects/lmd/
- ADL Piano MIDI: https://github.com/lucasnfe/adl-piano-midi
- Classical MIDI Archive: https://www.classicalmidi.co.uk/
- ASAP paper record: https://arxiv.org/abs/2008.07009

**Last reviewed:** September 2026
