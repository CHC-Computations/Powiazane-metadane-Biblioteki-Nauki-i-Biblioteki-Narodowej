![alt text](https://github.com/CHC-Computations/Harmonize/blob/main/logo-1.png?raw=true)
# Linked metadata of the Science Library and the National Library


# Enhancement of Biblioteka Nauki through Linked Metadata with the National Library

The **National Library** of Poland stands as one of the most venerable cultural institutions in the country, with its roots tracing back to the period of 1747-1795 when it operated as the Załuski Library. It was reinvigorated in the year 1928. The library is a formidable repository of books, periodicals, electronic and audiovisual publications issued within the Polish territory as well as foreign publications of Polish origin (polonica). It predominantly serves as a scholarly library with a humanities profile, the principal archive of national literature, a national hub for bibliographic information on books, a scientific institution, and a significant methodological center for libraries across Poland.

## Biblioteka Nauki: A Reservoir of Scientific Knowledge

**Biblioteka Nauki** is a dedicated platform offering full texts of scientific articles and selected books published in Polish journals. Its scope encompasses five major subject databases namely AGRO, BazTech, CEJSH, DML-PL, and PS, thereby serving as a rich source of scientific and scholarly material.

## Objective: Augmenting the Value and Usability of Biblioteka Nauki

The primary objective revolves around bolstering the utility and value of Biblioteka Nauki by aligning and matching its records with those of the National Library. This endeavor aims to enrich the metadata, thereby facilitating a more refined and accurate bibliographic information retrieval.

### Methodology Employed:

1. **Lemmatization of Titles**:
    - Employed the spacy tool and pl_core_news_lg model for lemmatizing titles, which is a crucial step towards ensuring consistency and eliminating linguistic variations.

2. **Text Normalization**:
    - Executed text normalization by removing Polish characters, special characters, uppercase letters, and spaces. This process is pivotal for preparing the data for subsequent comparison.

3. **String Comparison**:
    - Utilized the Levenshtein algorithm for string comparison, a robust method for measuring the difference between two sequences.

4. **Matching Threshold Establishment**:
    - Established a matching threshold of 0.86 ratio to ascertain the level of similarity required for a successful match.

### Outcome:

- Successfully matched 119,656 bibliographic records, the details of which have been encapsulated in two json files accessible on GitHub.
- Generated subject headings for Biblioteka Nauki leveraging the data from the National Library, thus enriching the bibliographic metadata and enhancing the searchability within Biblioteka Nauki.

The meticulous process of linking metadata between Biblioteka Nauki and the National Library not only augments the richness of bibliographic information but also paves the way for a more streamlined and effective data retrieval, serving the academic and research community at large.

## Repository Access

- The matched bibliographic records and other relevant data can be accessed and reviewed on [GitHub](https://github.com/CHC-Computations/Powiazane-metadane-Biblioteki-Nauki-i-Biblioteki-Narodowej/tree/main).
- The process underscores the importance of collaborative efforts in enhancing the data quality and accessibility in scholarly repositories.


![alt_text](https://github.com/CHC-Computations/Harmonize/blob/main/Zrzut%20ekranu%202022-12-19%20o%2017.48.49.png?raw=true)





