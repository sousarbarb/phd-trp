# Python Scripts from [slr-ltlm-mr](https://github.com/sousarbarb/slr-ltlm-mr)

1. [check_references](check_references/check_references.py)
   - **Input:** BibTex file exported from a data source
   - **Output:** processed BibText file with bibliographic fields normalization
   - Normalize the references to all have the following fields:
     - `author`
     - `ENTRYTYPE`
     - `volume`
     - `number`
     - `pages`
     - `url`
     - `doi`
     - `year`
     - `month`
     - `ID`
   - Generate a report to complete missing information in the references
2. [check_short_papers](check_short_papers/check_short_papers.py)
   - **Input:** CSV file exported from Parsifal
   - **Output:** list of potential short papers
   - Check the unclassified records in Parsifal that could be a short paper
