# Awesome Citation Formatting and Trust in Fabricated References

A curated research repository on **how citation presence, formatting, completeness, citation style, and identifiers such as DOIs/PMIDs can influence human trust in fabricated or unreliable references**, especially in AI-generated text.

This repository connects the earlier AI-assisted research paper with a verified literature collection, relevant datasets, citation-verification tools, open-source implementations, and learning resources. The goal is not to treat a citation as trustworthy merely because it looks complete: the repository emphasizes **independent verification, traceability, and human curation**.

## Contents

- [Overview](#overview)
- [AI-Assisted Research Paper](#ai-assisted-research-paper)
- [Research Papers](#research-papers)
  - [Citation Effects and Credibility Cues](#citation-effects-and-credibility-cues)
  - [Reference Accuracy and Scholarly Integrity](#reference-accuracy-and-scholarly-integrity)
  - [AI-Generated and Fabricated References](#ai-generated-and-fabricated-references)
- [Datasets](#datasets)
- [Tools and Libraries](#tools-and-libraries)
- [GitHub Implementations](#github-implementations)
- [Tutorials and Learning Resources](#tutorials-and-learning-resources)
- [Citation Integrity Audit](#citation-integrity-audit)
- [Curation and Verification Policy](#curation-and-verification-policy)
- [Repository Development](#repository-development)
- [License](#license)

## Overview

Citation systems are designed to make scholarly claims traceable to prior evidence. In practice, readers often encounter a citation before they verify the underlying source. This creates an important distinction between the **surface credibility of a citation** and the **actual reliability of the cited evidence**.

The research topic explored here is the influence of citation formatting on trust in fabricated references. The earlier research paper for this project argues that citation presence, completeness, conventional style, author names, journal information, and identifiers such as DOIs or PMIDs may act as credibility cues. This becomes especially important with large language models (LLMs), because AI systems can generate references that are fluent, conventional-looking, and sometimes completely nonexistent or bibliographically inaccurate.

The literature collected in this repository therefore spans three connected evidence streams: (1) cognitive and communication research on source cues, truth judgments, and credibility; (2) studies of reference accuracy and citation practices; and (3) empirical work documenting AI-generated citation fabrication and verification problems. A central unresolved issue is whether **specific citation-format features themselves causally change trust**, independently of citation presence and independently of whether the cited source is actually valid.

This repository is intended as a reusable research resource rather than a list of links. Each paper is accompanied by a short explanation of its relevance, and resources are grouped according to their role in the research workflow.

## AI-Assisted Research Paper

**Title:** *The Influence of Citation Formatting on Human Trust in Fabricated References: A Review of Citation Cues, Illusory Credibility, and the Emergence of AI-Fabricated Citations*

The paper synthesizes evidence on citation effects, source credibility, truthiness, reference fabrication, citation completeness, DOI/PMID cues, verification, and trust calibration.

[View the AI-Assisted Research Paper](paper/AI_Assisted_Research_Paper.pdf)

## Research Papers

### Citation Effects and Credibility Cues

- **The citation effect: In-text citations moderately increase belief in trivia claims** — Putnam & Phelps (2017), *Acta Psychologica*. Directly tests whether adding in-text citations changes truth judgments; useful as the central experimental foundation for citation-presence effects.
  [DOI](https://doi.org/10.1016/j.actpsy.2017.07.010)

- **Perceived credibility of Internet encyclopedias** — Kubiszewski, Noordewier & Costanza (2011), *Computers & Education*. Experimentally examines peripheral webpage cues including identifiable authors and references and their relationship to perceived credibility.
  [DOI](https://doi.org/10.1016/j.compedu.2010.10.008)

- **Nonprobative photographs (or words) inflate truthiness** — Newman et al. (2012), *Psychonomic Bulletin & Review*. Shows that non-evidential information can increase subjective truth, providing a broader cognitive mechanism relevant to citation surface cues.
  [DOI](https://doi.org/10.3758/s13423-012-0292-0)

- **Content versus source cue information as a basis for credibility judgments: The impact of task involvement** — Reinhard & Sporer (2010), *Social Psychology*. Examines how source cues and content information contribute differently to credibility judgments depending on task involvement.
  [DOI](https://doi.org/10.1027/1864-9335/a000014)

- **The influence of source cues and topic familiarity on credibility evaluation** — Lucassen & Schraagen (2013), *Computers in Human Behavior*. Shows that source cues can influence trust when information credibility is ambiguous.
  [DOI](https://doi.org/10.1016/j.chb.2013.01.036)

- **Source cues in online news: Is the proximate source more powerful than distal sources?** — Kang, Bae, Zhang & Sundar (2011), *Journalism & Mass Communication Quarterly*. Studies how different source cues affect perceived credibility under different levels of involvement.
  [DOI](https://doi.org/10.1177/107769901108800403)

- **Readers' perceptions of authors' citation behaviour** — Willett (2013), *Journal of Documentation*. Investigates whether readers correctly infer why authors cite sources, highlighting the interpretive role of citation context.
  [DOI](https://doi.org/10.1108/00220411311295360)

- **Starstruck by journal prestige and citation counts? On students' bias and perceptions of trustworthiness according to clues in publication references** — Eika & Sandnes (2022), *Scientometrics*. Studies how students judge reference trustworthiness using cues such as citation counts, recency, authorship, and publication information.
  [DOI](https://doi.org/10.1007/s11192-022-04521-4)

- **Not so different after all: Malaysian researchers' cross-discipline view of quality and trustworthiness in citation practices** — Abrizah et al. (2016), *Learned Publishing*. Surveys researchers' citation behaviour and the factors they associate with trustworthy scholarly communication.
  [DOI](https://doi.org/10.1002/leap.1032)

- **Practices of quality and trustworthiness in scholarly communication: A case from Pakistan** — Ameen (2017), *Learned Publishing*. Examines how academic researchers assess quality and trustworthiness in scholarly publishing and citation-related decisions.
  [DOI](https://doi.org/10.1002/leap.1094)

- **Citation Format Matters: Undergraduate Student Comprehension of Peer-Reviewed Scientific Manuscripts** — Cowan, Merritt & Mikan (2020), *The FASEB Journal*. Examines whether author-year versus numeric in-text citation formats affect readers' comprehension of scientific manuscripts.
  [DOI](https://doi.org/10.1096/fasebj.2020.34.s1.06442)

### Reference Accuracy and Scholarly Integrity

- **Citation Errors in Scientific Research and Publications: Causes, Consequences, and Remedies** — Agarwal (2023), *World Journal of Men's Health*. Discusses common citation errors, their causes, consequences, and the need to verify primary sources.
  [DOI](https://doi.org/10.5534/wjmh.230001)

- **Reference accuracy of primary studies published in peer-reviewed scholarly journals: A scoping review** — Logan et al. (2024), *Journal of Librarianship and Information Science*. Reviews 105 studies and reports a persistent problem of reference inaccuracy across scholarly fields.
  [DOI](https://doi.org/10.1177/09610006231177715)

- **Reference accuracy of primary studies about reference accuracy: A descriptive study** — Logan et al. (2025), *Journal of Librarianship and Information Science*. Verifies 1,486 references from studies about reference accuracy and reports an overall error rate of 21.2%.
  [DOI](https://doi.org/10.1177/09610006231224437)

- **Building Credibility with Comprehensive Citation Practices** — Subramanian, Soundararajan & Makol (2025), *Indian Journal of Radiology & Imaging*. Discusses citation practices, reference accuracy, citation styles, and their relationship to scholarly credibility.
  [DOI](https://doi.org/10.1055/s-0044-1796641)

### AI-Generated and Fabricated References

- **Artificial Hallucinations in ChatGPT: Implications in Scientific Writing** — Alkaissi & McFarlane (2023), *Cureus*. Early discussion of hallucinated AI content and its implications for scientific writing.
  [DOI](https://doi.org/10.7759/cureus.35179)

- **Exploring the Boundaries of Reality: Investigating the Phenomenon of Artificial Intelligence Hallucination in Scientific Writing Through ChatGPT References** — Athaluri et al. (2023), *Cureus*. Examines hallucinated references in ChatGPT-generated scientific proposals.
  [DOI](https://doi.org/10.7759/cureus.37432)

- **High Rates of Fabricated and Inaccurate References in ChatGPT-Generated Medical Content** — Bhattacharyya et al. (2023), *Cureus*. Measures fabricated and inaccurate references in ChatGPT-generated medical papers and verifies them against scholarly databases.
  [DOI](https://doi.org/10.7759/cureus.39238)

- **Learning to Fake It: Limited Responses and Fabricated References Provided by ChatGPT for Medical Questions** — Gravel, D'Amours-Gravel & Osmanlliu (2023), *Mayo Clinic Proceedings: Digital Health*. Reports that many references generated in response to medical questions were fabricated despite appearing realistic.
  [DOI](https://doi.org/10.1016/j.mcpdig.2023.05.004)

- **A Preliminary Investigation of Fake Peer-Reviewed Citations and References Generated by ChatGPT** — Day (2023), *The Professional Geographer*. Early empirical investigation showing that ChatGPT can produce non-existent scholarly references.
  [DOI](https://doi.org/10.1080/00330124.2023.2190373)

- **Accuracy of Information and References Using ChatGPT-3 for Retrieval of Clinical Radiological Information** — Wagner & Ertl-Wagner (2024), *Canadian Association of Radiologists Journal*. Evaluates both answer accuracy and the authenticity/usefulness of 343 generated references.
  [DOI](https://doi.org/10.1177/08465371231171125)

- **Fabrication and errors in the bibliographic citations generated by ChatGPT** — Walters & Wilder (2023), *Scientific Reports*. Large cross-disciplinary study of fabricated citations, bibliographic errors, formatting errors, and hyperlinks in GPT-3.5/GPT-4 outputs.
  [DOI](https://doi.org/10.1038/s41598-023-41032-5)

- **Evaluation of Large Language Model Performance and Reliability for Citations and References in Scholarly Writing: Cross-Disciplinary Study** — Mugaanyi et al. (2024), *Journal of Medical Internet Research*. Compares citation/reference reliability across natural sciences and humanities and examines DOI-related errors.
  [DOI](https://doi.org/10.2196/52935)

- **Citation integrity in the age of AI: evaluating the risks of reference hallucination in maxillofacial literature** — Jain, Nimonkar & Jadhav (2025), *Journal of Cranio-Maxillofacial Surgery*. Reviews reference hallucination risks and discusses implications for academic and clinical trust.
  [DOI](https://doi.org/10.1016/j.jcms.2025.08.004)

- **Evaluating the Integrity of LLM-Generated Citations: Prevalence and Risks of Fabricated References in Scientific Literature** — Picazo-Sanchez & Ortiz-Martin (2026), *Data*. Examines large-scale LLM-generated bibliographic references and potential fabricated references in published literature.
  [DOI](https://doi.org/10.3390/data11050122)

- **Phantom citations: An empirical study of non-existent and unverifiable references in scholarly literature** — Han, Manoharan, Ye & Speidel (2026), *Journal of the Association for Information Science and Technology*. Develops an auditable pipeline for identifying unresolved and unverifiable references in scholarly papers.
  [DOI](https://doi.org/10.1002/asi.70104)

- **How Unique Are Hallucinated Citations Offered by Generative Artificial Intelligence Models?** — Spennemann (2026), *Publications*. Studies repeated hallucinated references and how plausible-looking references can propagate through later documents.
  [DOI](https://doi.org/10.3390/publications14030038)

- **Hallucinated citations produced by generative artificial intelligence may constitute research misconduct when citations function as data in scholarly papers** — Resnik & Hosseini (2026), *Accountability in Research*. Examines ethical and regulatory implications of unchecked hallucinated citations in scholarly work.
  [DOI](https://doi.org/10.1080/08989621.2026.2645390)

## Datasets

See [datasets/datasets.md](datasets/datasets.md).

- **SciFact** — scientific claim verification with cited documents and evidence labels.
- **SciCite** — citation-intent classification across scientific domains.
- **S2ORC** — large-scale scholarly corpus with resolved bibliographic references and citation links.

## Tools and Libraries

See [tools/tools.md](tools/tools.md).

- **Crossref REST API** — authoritative DOI and bibliographic metadata retrieval.
- **OpenAlex** — open scholarly graph and works metadata.
- **Semantic Scholar API** — paper, author, citation, and reference metadata.
- **GROBID** — PDF-to-structured scholarly-document and reference extraction.
- **Zotero** — reference management and bibliography organization.

## GitHub Implementations

See [implementations/github-repositories.md](implementations/github-repositories.md).

These are independent open-source projects selected because they implement practical citation extraction, verification, or hallucination-detection workflows. They are **not copied into this repository**.

## Tutorials and Learning Resources

See [tutorials/learning-resources.md](tutorials/learning-resources.md).

## Citation Integrity Audit

[View the repository citation-integrity audit](citation-audit/Citation_Integrity_Audit.pdf)

The audit documents the verification approach used for this curated collection. It distinguishes:
1. existence of the cited work,
2. metadata consistency,
3. identifier/DOI resolution,
4. source-link correctness, and
5. relevance to this research topic.

## Curation and Verification Policy

This repository follows the central rule of the course activity: **a reference is not accepted merely because an AI system generated it**.

For scholarly papers, the preferred verification order is:
1. Publisher or journal record.
2. DOI/Crossref record where applicable.
3. PubMed for biomedical literature where applicable.
4. ACL Anthology for computational-linguistics papers.
5. Semantic Scholar/OpenAlex as secondary metadata and discovery systems.

For GitHub resources, selection considers documentation, source-code availability, maintenance/activity, reproducibility, licensing, and relevance to citation verification.

No third-party copyrighted research-paper PDFs are redistributed here. The `paper/` directory contains the student's own earlier research paper.

## Repository Development

The repository is designed to demonstrate meaningful Git history. The prepared version contains six meaningful development commits:

1. `Initial repository structure`
2. `Add AI-assisted research paper`
3. `Add verified research-paper collection`
4. `Add datasets, tools and learning resources`
5. `Add citation-verification GitHub implementations`
6. `Finalize README and citation-integrity audit`

## Submission Information

Fill these values before submitting:

- **Student Name:** `Anuj Gola`
- **Roll Number:** `MRA2026011`
- **Assigned Research Topic:** `The Influence of Citation Formatting on Human Trust in Fabricated References`
- **GitHub Profile URL:** `https://github.com/GolaAnuj`
- **Awesome Repository URL:** `https://github.com/YOUR_USERNAME/awesome-citation-formatting-trust`
- **Repository Name:** `awesome-citation-formatting-trust`

## License

This repository's original documentation and curation material is released under the MIT License. Individual linked papers, datasets, and third-party repositories remain under their respective licenses.
