# citedown

This is code for making Markdown-compatible citations. Usage:

    citedown.py <PUBMEDID>

For example,

    citedown.py 11834560
    
Yields the output:

    [Schroeder 2002]: https://www.ncbi.nlm.nih.gov/pubmed/11834560/ "Schroeder K, Fahey T. Systematic review of randomised controlled trials of over the counter cough medicines for acute cough in adults. BMJ. 2002 Feb 9;324(7333):329-31. Review. PubMed PMID: 11834560; PubMed Central PMCID: PMC65295."
    
Which can be pasted into the bottom of a Markdown blog post, allowing you to simply type \[Schroeder 2002\] inline to cite this paper.
