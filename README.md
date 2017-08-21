# ASRC2017 - Will be publicly available a week before SIGIR2017 conference.
  Adversarial Search Collection 2017. 
  Information Retrieval Meets Game Theory: The Ranking Competition Between Documents' Authors.


# The ASR Collection (collection):
    
    The collection contains 1279 documents, 
    31 initial relevant documents (round 0) and 1248 documents (rounds 1-8) created by authors, 
    897 of which are unique.
    
    Format: trectext.
    DOCNO Format: ROUND-<round_number>-<query_id>-<author_id>

# Relevance Judgments (qrels):
    
    All documents in the collection were judged for relevance. 
    Annotators were presented with both the title and the description of each TREC topic
    and were asked to classify a document as relevant if it satisfies the information need stated in the description.
    
    A document judged relevant by less than three annotators was labeled as non-relevant (0).
    Documents judged relevant by at least three, four or five annotators 
    were labeled as marginally relevant (1), fairly relevant (2) and highly relevant (3), respectively.
    
# Keyword Stuffing Judgments (ksrels):
    
    A document was annotated as keyword stuffed if it contained excessive repetition of words 
    which seemed unnatural or artificially introduced.
    Each document was judged by five annotators. 
    
    A document judged keyword stuffed by less than four annotators was labeled as non-keyword-stuffed (0).
    Documents judged keyword stuffed by at least four or five annotators were labeled as keyword-stuffed (1).

# Queries
    We used the ClueWeb09 queries which can be downloded here: http://trec.nist.gov/data/webmain.html.
# Extened Information About The Collection:
    
    To shed some light on the strategic behaviour of document authors (publishers) 
    we organized repeated ranking competitions.
    52 senior-undergrad and grad students in an information retrieval course were the publishers.
    The competition included 31 different repeated matches, 
    each of which was with respect to a different TREC's ClueWeb09 query.
    
    Each publisher participated in three matches and 5 publishers competed against each other in all matches 
    excpet for one in which 6 publishers were competed.
    The competition was run for 8 rounds; i.e., there were eight matches per query.
    Before the first round an example or a relevant document was provided 
    for each match to all publishers (round 0).
    All documents were unstructured plain text of up to 150 terms and the document ranking model 
    was based on LambdaMART learning-to-rank approach.
    
    For further info please read the paper: 
    "Information Retrieval Meets Game Theory: The Ranking Competition Between Documents' Authors."
    
# Citations
  If you use the ASRC dataset in your work, please cite it as:

      @inproceedings{DBLP:conf/sigir/RaiferRTK17,
      author    = {Nimrod Raifer and
                   Fiana Raiber and
                   Moshe Tennenholtz and
                   Oren Kurland},
      title     = {Information Retrieval Meets Game Theory: The Ranking Competition Between
                   Documents? Authors},
      booktitle = {Proceedings of the 40th International {ACM} {SIGIR} Conference on
                   Research and Development in Information Retrieval, Shinjuku, Tokyo,
                   Japan, August 7-11, 2017},
      pages     = {465--474},
      year      = {2017},
      crossref  = {DBLP:conf/sigir/2017},
      url       = {http://doi.acm.org/10.1145/3077136.3080785},
      doi       = {10.1145/3077136.3080785},
      timestamp = {Sun, 06 Aug 2017 18:21:32 +0200},
      biburl    = {http://dblp.uni-trier.de/rec/bib/conf/sigir/RaiferRTK17},
      bibsource = {dblp computer science bibliography, http://dblp.org}
    }
