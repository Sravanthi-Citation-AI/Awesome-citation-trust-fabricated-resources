# Tools and Libraries

## Topic

**The Influence of Citation Formatting on Human Trust in Fabricated Resources**

This file documents tools that can help researchers discover scholarly literature, verify citation metadata, manage references, and investigate whether AI-generated citations are authentic.

> **Use note:** These are external research tools and services. The repository links to their official websites or documentation rather than copying software or datasets into this repository.

## 1. Crossref

**Official website:** https://www.crossref.org/

**REST API documentation:** https://www.crossref.org/documentation/retrieve-metadata/rest-api/

**Purpose:** Crossref provides open scholarly metadata and a REST API for searching and retrieving bibliographic records.

**Key capabilities:**
- DOI lookup
- Article and journal metadata retrieval
- Author and publication information
- Reference metadata
- Search and filtering through the REST API

**Relevance to this project:** Crossref is particularly useful for citation-integrity auditing because a DOI can be checked against the metadata registered for a scholarly work. It can help verify whether a cited title, author list, publication venue, date, and DOI correspond to an actual record.

**Verification use:** Compare the citation in the research paper with the Crossref record instead of trusting the citation's appearance.

Crossref states that its REST API exposes scholarly metadata deposited by members and trusted sources, and its metadata can be accessed without registration.  
Source: https://www.crossref.org/documentation/retrieve-metadata/rest-api/

---

## 2. Semantic Scholar

**Official website:** https://www.semanticscholar.org/

**API documentation:** https://api.semanticscholar.org/api-docs/

**Purpose:** Semantic Scholar is an academic search and discovery platform with APIs for retrieving information about papers, authors, citations, and references.

**Key capabilities:**
- Scholarly paper search
- Author lookup
- Citation and reference information
- Paper recommendations
- Academic Graph API
- Research datasets

**Relevance to this project:** It can be used as a second scholarly source when checking whether a paper exists and when examining relationships between papers, citations, authors, and references.

**Verification use:** Cross-check suspicious or AI-generated references against another scholarly index after checking authoritative publisher or DOI records.

Source: https://api.semanticscholar.org/api-docs/

---

## 3. OpenAlex

**Official website:** https://openalex.org/

**Documentation:** https://docs.openalex.org/

**Purpose:** OpenAlex is an open catalog of scholarly works, authors, institutions, sources, and related research entities.

**Key capabilities:**
- Scholarly work discovery
- Author and institution information
- Citation relationships
- Research-topic discovery
- Open scholarly metadata

**Relevance to this project:** Open scholarly metadata can support literature discovery and cross-checking of bibliographic information when investigating citation authenticity.

**Verification use:** Search a title or author and compare the returned work, publication venue, date, and citation relationships with the reference being audited.

---

## 4. Zotero

**Official website:** https://www.zotero.org/

**Documentation:** https://www.zotero.org/support/quick_start_guide

**Purpose:** Zotero is a free reference manager for collecting, organizing, citing, and sharing research sources.

**Key capabilities:**
- Save and organize references
- Store bibliographic metadata
- Generate citations and bibliographies
- Support for APA, MLA, Chicago, Vancouver, and many other styles
- Word, LibreOffice, and Google Docs integration
- PDF organization and annotation

**Relevance to this project:** Zotero helps maintain consistent citation formatting and organize the verified references used in the research project.

**Verification use:** Import references using DOI or other bibliographic information, then compare the metadata with authoritative records before using a citation.

Zotero documentation describes it as a reference manager and explains its citation-style and bibliography features.  
Source: https://www.zotero.org/support/quick_start_guide

---

## 5. Google Scholar

**Official website:** https://scholar.google.com/

**Purpose:** Google Scholar provides a broad search interface for scholarly literature across articles, theses, books, conference papers, and other academic sources.

**Key capabilities:**
- Scholarly literature search
- Author and publication discovery
- Citation counts and cited-by links
- Related articles
- Library and publisher links where available

**Relevance to this project:** Google Scholar can help discover literature related to citation credibility, human trust, AI hallucination, and fabricated references.

**Verification use:** Use it as a discovery and cross-checking resource. For final citation verification, confirm important metadata against the publisher, DOI registry, journal site, or another authoritative record.

---

## Tool Comparison

| Tool | Main purpose | Best use in this project |
|---|---|---|
| Crossref | Scholarly metadata and DOI services | Verify DOI and bibliographic metadata |
| Semantic Scholar | Academic discovery and citation graph | Cross-check papers, authors, citations, and references |
| OpenAlex | Open scholarly catalog | Discover and cross-check scholarly works and relationships |
| Zotero | Reference management | Organize verified sources and format citations |
| Google Scholar | Scholarly search and discovery | Find literature and locate related research |

## Recommended Citation-Verification Workflow

For a suspicious or AI-generated citation:

1. **Search the exact title** in Crossref, Google Scholar, Semantic Scholar, or OpenAlex.
2. **Check whether the publication exists.**
3. **Compare the authors and title** with the authoritative record.
4. **Check the publication year and journal/conference.**
5. **Check the DOI or other identifier** when one is supplied.
6. **Open the publisher or DOI record** for the strongest confirmation.
7. **Check whether the source actually supports the claim** for which it is cited.
8. Record the result in the repository's citation-integrity audit.

## Why These Tools Matter

A professional-looking citation is not proof that a source exists. The tools above provide different forms of evidence:

- **Crossref** provides structured DOI and bibliographic metadata.
- **Semantic Scholar and OpenAlex** provide scholarly discovery and citation relationships.
- **Google Scholar** helps locate relevant scholarly literature.
- **Zotero** helps keep verified references organized and consistently formatted.

Using more than one discovery tool is useful, but the final authenticity decision should rely on authoritative publication or identifier records whenever possible.

## Sources

- Crossref REST API: https://www.crossref.org/documentation/retrieve-metadata/rest-api/
- Semantic Scholar API: https://api.semanticscholar.org/api-docs/
- Zotero Quick Start Guide: https://www.zotero.org/support/quick_start_guide
- OpenAlex Documentation: https://docs.openalex.org/
- Google Scholar: https://scholar.google.com/
