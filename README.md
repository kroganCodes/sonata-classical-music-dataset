<div align="center">

# 🎹 SONATA (Augmented MAESTRO)
### **S**ymmetrically **O**rchestrated **N**otes and **A**udio for **T**ransformer **A**rchitectures

**SONATA** stands for **Symmetrically Orchestrated Notes and Audio for Transformer Architectures**: a balanced audio-symbolic benchmark built to help models learn musical-era characteristics rather than dataset imbalance.

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-blue.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Audio Modality](https://img.shields.io/badge/Audio-44.1kHz_16--bit_PCM_WAV-brightgreen.svg)]()
[![Symbolic Modality](https://img.shields.io/badge/Symbolic-SMF_Type_0%2F1_MIDI-orange.svg)]()
[![Dataset Balance](https://img.shields.io/badge/Distribution-Exact_200%2FEra_Symmetric-purple.svg)]()
[![Corpus Scale](https://img.shields.io/badge/Scale-133.30_Hours_%7C_4.47M_Notes-crimson.svg)]()
[![Python 3.9+](https://img.shields.io/badge/Python-3.9%2B-blue.svg)]()

<p align="center">
   <b>The Next-Generation Cross-Modal Benchmark for Classical Music Era Classification & Audio-Symbolic Transformers</b>
</p>

---

</div>

## 🌟 Executive Pitch: The Next Big Thing in Music AI & Classification

For nearly a decade, Google Magenta's **MAESTRO** (*MIDI and Audio Edited for Synchronous TRacks and Organization*) has stood as a leading benchmark for machine learning in expressive piano performance. Yet for macro-temporal semantic tasks, especially **Musical Era Classification**, MAESTRO is strongly skewed toward Romantic repertoire.

When modern deep learning models are trained on heavily imbalanced benchmarks, they can learn a majority-class shortcut instead of the contrapuntal, harmonic, and morphological language of Western art music. SONATA addresses this problem by combining acoustic performance data with symbolic music and balancing six historical eras.

### Enter **SONATA (Augmented MAESTRO)**

SONATA fuses **Google Magenta MAESTRO**, the **ASAP Dataset**, the **ADL Piano MIDI Dataset**, and curated material from the **Classical MIDI Archive**. The result is a balanced, cross-modal classical music benchmark for era classification, audio analysis, symbolic learning, and multimodal research.

---

## 🌍 Why SONATA matters

SONATA is not just another dataset. It is a new benchmark designed to confront one of the biggest unresolved problems in music information retrieval: the inability of modern models to reliably classify musical eras when the historical data is skewed, fragmented, and dominated by a few famous composers.

For years, the field has relied heavily on MAESTRO as a strong benchmark for piano performance modeling, but MAESTRO is not built for era-level musical understanding. Its distribution is deeply imbalanced and strongly centered on Romantic repertoire, which means a model can appear highly accurate while simply learning a majority-class shortcut rather than genuinely understanding musical style, form, and historical identity.

SONATA fixes that.

By combining the strengths of:

- Google Magenta MAESTRO
- ASAP
- ADL Piano MIDI
- Classical MIDI Archive
- curated historical piano repertoire spanning multiple eras

SONATA creates a balanced, high-quality, cross-modal dataset for Western classical music that is explicitly designed for audio classification, symbolic analysis, multimodal learning, and era recognition tasks.

This is the kind of dataset that can help move the field from "music classification as a toy benchmark" to "music understanding as a real scientific problem."

---

## ⬇️ Download the complete dataset

The complete 84.7 GB SONATA corpus is hosted on Hugging Face, where users can download the full audio and MIDI collection:

**[Download SONATA on Hugging Face](https://huggingface.co/datasets/kroganCodes/sonata-classical-music-dataset)**

This GitHub repository keeps the documentation, reports, licensing notice, and metadata available for review before downloading the large corpus. The CSV manifests can be inspected directly here:

- [balanced_dataset.csv](balanced_dataset.csv)
- [sonata_dataset.csv](sonata_dataset.csv)
- [LICENSES.md](LICENSES.md)

The Hugging Face dataset contains the complete `audio/` and `midi/` folders together with the CSV files, reports, README, and licensing notice.

### Download options

**Full dataset:** Open the Hugging Face link above, click **Files and versions**, and download the files or folders you need. For command-line downloads, install the Hugging Face client and run:

```powershell
hf download kroganCodes/sonata-classical-music-dataset --repo-type dataset --local-dir SONATA
```

**GitHub metadata and documentation:** This public GitHub repository is designed for quick review. Use **Code -> Download ZIP** or clone it with:

```powershell
git clone https://github.com/kroganCodes/sonata-classical-music-dataset.git
```

The GitHub download contains the README, reports, licensing notice, and CSV manifests. The 84.7 GB `audio/` and `midi/` folders are hosted on Hugging Face because GitHub is not designed for files of that size.

---

## 💎 The Four Pillars of Dataset Fusion

SONATA unites four complementary sources into one cohesive research resource:

1. **Google Magenta MAESTRO**: high-quality expressive piano performance data with aligned audio and MIDI.
2. **ASAP Dataset**: score-aligned piano performances with human timing and expressive nuance.
3. **ADL Piano MIDI Dataset**: structured piano MIDI coverage that adds symbolic and pedagogical diversity.
4. **Classical MIDI Archive**: historical repertoire that expands coverage beyond the standard benchmark bias.

This combination gives SONATA both acoustic realism and symbolic richness, making it useful for audio-only, MIDI-only, and multimodal pipelines.

---

## 🚀 The Next Big Thing in Music AI

The world is rapidly moving toward multimodal foundation models for audio, language, and symbolic music. Yet classical music remains one of the hardest domains for representation learning because of:

- severe class imbalance
- scarce historical coverage
- inconsistent annotation quality
- high variability in performance style
- limited data for underrepresented eras

SONATA was built to address exactly these gaps.

It is a large-scale, era-balanced, audio-symbolic dataset spanning:

- Baroque
- Classical
- Romantic
- Late Romantic
- Impressionist
- Modern

Every era is represented with equal weighting and rigorous curation, enabling researchers to train models that learn features tied to historical style rather than dataset bias.

This makes SONATA a compelling resource for:

- music era classification
- multimodal representation learning
- audio-to-symbolic alignment
- piano performance modeling
- style transfer research
- music historical analysis
- cross-domain benchmark evaluation

In short, SONATA is positioned as a foundational benchmark for the next generation of music AI systems.

---

## 🧩 What makes SONATA different

SONATA is a fusion dataset built for realism and scientific rigor. It is not a random mixture of MIDI files and WAVs—it is curated, balanced, and standardized for research use.

### Core sources

1. MAESTRO
   - High-quality piano performance data
   - Strong acoustic ground truth
   - Benchmark-level alignment with expressive music capture

2. ASAP
   - Score-aligned piano performance data
   - Human timing and expressive nuance
   - Strong symbolic alignment and musical structure information

3. ADL Piano MIDI
   - Structured piano MIDI coverage
   - Useful for stylistic and symbolic learning
   - Adds historical and compositional diversity

4. Classical MIDI Archive
   - Historical repertoire from important classical and piano collections
   - Expands coverage beyond the standard benchmark bias
   - Brings compositional breadth and era diversity

This combination gives SONATA both acoustic realism and symbolic richness, making it useful for audio-only, MIDI-only, and multimodal pipelines.

---

## 📊 Dataset composition

SONATA provides exact symmetrically balanced coverage across six major eras of Western art music.

| Musical Era | Total Tracks | Audio Files | MIDI Files | Duration |
| :--- | :---: | :---: | :---: | :---: |
| Baroque | 200 | 200 | 200 | 14.82 hrs |
| Classical | 200 | 200 | 200 | 26.14 hrs |
| Romantic | 200 | 200 | 200 | 25.48 hrs |
| Late Romantic | 200 | 200 | 200 | 23.95 hrs |
| Impressionist | 200 | 200 | 200 | 20.73 hrs |
| Modern | 200 | 200 | 200 | 22.18 hrs |
| TOTAL | 1,200 | 1,200 | 1,200 | 133.30 hrs |

Across the full corpus:

- 1,200 paired audio and MIDI examples
- 133.30 total hours of piano music
- more than 4.47 million note events
- exact distribution parity across era classes

This is one of the strongest practical foundations for historical music classification and multimodal modeling in the classical domain.

---

## 🏗️ Why it matters for machine learning

Most classical music datasets are either:

- too small,
- too skewed,
- too focused on one style,
- or too symbolic without acoustic realism.

SONATA was designed to remove those bottlenecks.

The result is a benchmark where models can be trained and compared fairly across eras without trivial majority-class bias dominating the learning process. That matters because the field is no longer asking whether a model can classify a single genre—it is asking whether a model can understand historical style, structure, and expression across a large and diverse repertoire.

This is the foundation for the next generation of:

- music taggers
- piano recognition systems
- stylistic embeddings
- era classification models
- symbolic-audio transformers
- cross-modal MIR systems

---

## 📦 Repository structure

The dataset is organized in a dedicated SONATA folder. The compressed archive contains the full audio and MIDI material so that users can download the dataset, extract it, and work with the complete collection locally.

```text
SONATA/
├── audio/
│   ├── baroque/
│   ├── classical/
│   ├── romantic/
│   ├── late_romantic/
│   ├── impressionist/
│   └── modern/
├── midi/
│   ├── baroque/
│   ├── classical/
│   ├── romantic/
│   ├── late_romantic/
│   ├── impressionist/
│   └── modern/
├── balanced_dataset.csv
├── sonata_dataset.csv
├── README.md
└── SONATA.zip
```

The package is designed to be transparent and easy to use:

- the dataset is downloadable as a zip archive
- extracting it gives the full audio/MIDI structure
- the CSV manifest provides metadata and split information
- the reports remain available for documentation and publication references
- source-specific license and redistribution notes are provided in [LICENSES.md](LICENSES.md)
- the complete public mirror will be linked here after rights review and hosting are finalized

---

## ⚡ Quickstart: Loading SONATA with PyTorch

Download the SONATA archive from the repository release, extract it, and use the extracted `SONATA` folder as the dataset root. The manifest stores paths relative to that folder.

```python
from pathlib import Path
import pandas as pd

root_dir = Path("SONATA")
manifest = pd.read_csv(root_dir / "sonata_dataset.csv")

row = manifest.iloc[0]
audio_path = root_dir / row["audio_filename"]
midi_path = root_dir / row["midi_filename"]

print(row["era"])
print(audio_path)
print(midi_path)
```

For a PyTorch pipeline, load audio with `torchaudio.load(audio_path)` and MIDI with `pretty_midi.PrettyMIDI(str(midi_path))`. If you extract the archive somewhere else, replace `Path("SONATA")` with the extracted folder path.

---

## 🔬 Scientific value

SONATA is useful not only as a dataset but as a benchmark for how modern models should handle historical representation learning.

By balancing and standardizing across eras, it allows researchers to ask more meaningful questions:

- Can a model distinguish Baroque counterpoint from Romantic expression?
- Can it detect stylistic transformations across late Romantic and Impressionist textures?
- Can it generalize across audio and symbolic views of the same piece?
- Does the model learn musically meaningful invariants rather than simple class priors?

This is the kind of benchmark that pushes the field forward from shallow pattern matching to deeper musical understanding.

---

## ✅ Why we believe this is the start of something big

SONATA is designed to be more than a dataset release. It is a new benchmark contribution for the music AI community.

It blends the strongest available resources in the field into a coherent, balanced, and researcher-friendly benchmark. It is built for the next generation of models, the next generation of music understanding research, and the next generation of audio-symbolic AI.

This is a dataset that brings together:

- expressive piano performance
- symbolic notation and MIDI structure
- historical diversity
- balanced era coverage
- realistic cross-modal research potential

That combination is exactly what makes it exciting.

---

## 📚 Citation

If you use SONATA in academic work, please cite the dataset as:

```bibtex
@dataset{sonata_augmented_maestro_2026,
   title = {A Hybrid CNN–Transformer–VAE Framework for Classical Music Era Classification},
   author = {Aryan Rahman Mugdha and Saadman Bin Jashim},
   year = {2026},
   publisher = {GitHub},
   note = {A balanced multimodal classical music dataset combining MAESTRO, ASAP, ADL Piano MIDI, and the Classical MIDI Archive}
}
```

For attribution, redistribution conditions, and the rights status of the underlying source collections, see [LICENSES.md](LICENSES.md).

---

## 🙌 Final statement

SONATA stands at the intersection of classical music scholarship, machine learning, and multimodal AI. It is a benchmark for era-aware music understanding, built to address imbalance, expand historical coverage, and create a more serious foundation for future research.

This is not just a classical music dataset. This is the kind of dataset that can help define the next era of music intelligence.
