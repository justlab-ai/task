# Clinical Datasets for LLM Evaluation

Research on the best datasets for evaluating LLM ability to summarize patient-doctor conversations into organized clinical notes and EHR documents.

## Primary Choice: ACI-Bench

Best overall public benchmark for evaluating "AI scribe" / clinical-note LLMs.

- **What it is**: Large corpus of clinician-patient conversation transcripts paired with visit notes (SOAP-style)
- **Why it's strong**:
  - Multi-specialty dataset with realistic note-length
  - Publicly released via GitHub/FigShare with code and baselines
  - Used in multiple recent benchmarking papers on ambient clinical documentation
- **Best use**: Quantitative benchmarking of "conversation → structured visit note" systems

## Secondary Benchmarks

| Dataset | Size | Description | Best Use |
|---------|------|-------------|----------|
| **MTS-Dialog** | ~1.7k dialogues | Doctor-patient dialogues with clinical notes across multiple note types | Text-only transcript → note, comparing against prior literature |
| **PriMock57** | 57 consultations | Mock primary-care consultations with audio, transcripts, and notes | High-fidelity human evaluation, audio → transcript → note |
| **CliniKnote** | ~1,200 conversations | Complex simulated conversations with K-SOAP notes | Complex long conversations, structured notes |

## Other Notable Datasets

| Dataset | Description | Best Use |
|---------|-------------|----------|
| **NoteChat** | ~100k+ synthetic dialogues conditioned on clinical notes | Pre-training / data augmentation |
| **Microsoft Clinical Visit Note Summarization Corpus** | Synthetic clinical encounters | NLG method testing |

## Recommended Evaluation Protocol

1. **Primary benchmark**: ACI-Bench
   - Main quantitative metrics (ROUGE, BERTScore, BLEURT)
   - Comparing against published SOTA

2. **Secondary benchmark**: MTS-Dialog
   - Sectioned notes and diverse note styles
   - Continuity with prior work

3. **Human evaluation**: PriMock57
   - Small-scale, high-quality clinician ratings
   - End-to-end audio → note pipelines

4. **Advanced evaluation** (if accessible): CliniKnote
   - Complex, long conversations
   - K-SOAP structured notes (Keyword + SOAP)

## References

- [ACI-Bench Paper](https://www.nature.com/articles/s41597-023-02487-3)
- [MTS-Dialog GitHub](https://github.com/abachaa/MTS-Dialog)
- [NoteChat Paper](https://arxiv.org/html/2310.15959v2)
