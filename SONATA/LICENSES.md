# SONATA Licensing, Attribution, and Redistribution Notice

**Dataset authors:** Aryan Rahman Mugdha and Saadman Bin Jashim

**Dataset:** SONATA (Augmented MAESTRO)

This file records the source-license information reviewed for the SONATA project. It is an attribution and rights notice, not a grant of rights over third-party recordings or MIDI files. SONATA is a derived compilation, and each source component remains subject to its own terms.

## Important distribution status

The complete SONATA corpus must not be represented as a single blanket open-source or Creative Commons release unless redistribution permission has been verified for every included file. The source materials have different rights statuses. A public-domain composition does not automatically make a particular recording, MIDI sequence, or transcription free to redistribute.

For a public mirror such as Hugging Face, upload only files for which redistribution rights are documented, or obtain written permission from the relevant rightsholders before uploading the complete derived corpus. A metadata-only release that points users to the original sources is the safer fallback.

## Source-by-source status

### Google Magenta MAESTRO v3.0.0

- Stated license: Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0).
- Official source: https://magenta.tensorflow.org/datasets/maestro
- Retain attribution, link the license, identify modifications, and do not use the material commercially. Adapted material must follow compatible ShareAlike terms.
- Citation: Curtis Hawthorne et al., “Enabling Factorized Piano Music Modeling and Generation with the MAESTRO Dataset,” ICLR 2019.

### ASAP

- Project cited in the SONATA reports: Foscarin et al., “ASAP: a dataset of aligned scores and piano performances,” ISMIR 2020.
- The reports do not include a license notice for the exact ASAP files incorporated into SONATA, and the upstream license could not be verified from the project materials available here.
- Redistribution status: unverified. Do not redistribute these files publicly until the exact upstream license or written permission is confirmed.

### ADL Piano MIDI

- Project page: https://github.com/lucasnfe/adl-piano-midi
- Citation: Lucas N. Ferreira, Levi H. S. Lelis, and Jim Whitehead, “Computer-Generated Music for Tabletop Role-Playing Games,” AIIDE 2020.
- The ADL README describes a collection assembled from the Lakh MIDI Dataset and additional MIDI files scraped from publicly available internet sources. It does not provide one blanket redistribution license for all files.
- The underlying Lakh MIDI Dataset states CC BY 4.0 and requests attribution to Colin Raffel: https://colinraffel.com/projects/lmd/
- Lakh-derived files may have CC BY 4.0 terms, but the additional scraped ADL files require source-level verification. Do not assume the entire ADL collection is CC BY 4.0.

### Classical MIDI Archive

- Website: https://www.classicalmidi.co.uk/
- The site states that MIDI pieces are not automatically free of copyright, asks users to contact the relevant sequencer for non-commercial use, and grants permission for the webmaster’s own sequences only when due credit and a link back to the site are provided.
- Redistribution status: restricted / not blanket-open. Obtain permission for each included sequence or remove those files from a public mirror.
- A public-domain composition may still have a protected MIDI arrangement or recording.

## SONATA-authored material

The SONATA authors created the balancing, organization, metadata, processing, quality-control documentation, and derived annotations described in the reports. Those project contributions are attributed to Aryan Rahman Mugdha and Saadman Bin Jashim. They do not override upstream rights.

The reports and metadata may be shared with attribution, but audio and MIDI files must follow the most restrictive applicable upstream terms. A platform dataset-license field must not imply that the maintainers own or relicense third-party content.

## Required attribution block

> SONATA (Augmented MAESTRO), by Aryan Rahman Mugdha and Saadman Bin Jashim. SONATA is a balanced derived compilation and processing of material from MAESTRO, ASAP, ADL Piano MIDI, and Classical MIDI Archive sources. See the source-specific rights notices in `LICENSES.md`.

**Last reviewed:** September 2026
