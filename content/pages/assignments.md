---
content_type: page
title: Assignments
uid: 48a8a6b4-bb3a-c5c6-9c7c-63540f644c1f
---

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
ASSIGNMENTS
{{< thclose >}}
{{< thopen >}}
SUPPORTING FILES
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
Homework 1 ([PDF]({{< baseurl >}}/resources/hw1))
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Homework 2 ([PDF]({{< baseurl >}}/resources/hw2))
{{< tdclose >}}
{{< tdopen >}}
counts.gz ([GZ - 3.2 MB]({{< baseurl >}}/resources/counts)) (The GZ file contains: counts.txt.)  
theirthere.test ([TXT](/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/assignments/theirtheretest.txt))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Homework 3 ([PDF]({{< baseurl >}}/resources/hw3))
{{< tdclose >}}
{{< tdopen >}}
data.gz ([GZ]({{< baseurl >}}/resources/data)) (The GZ file contains: data.txt.)  
synrev ([TXT](/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/assignments/synrev.txt))  
  
_Development Data_  
  
Verb pairs and associated cosine similarity scores (note that sim.in = synrev).  
sim.in ([TXT](/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/assignments/simin.txt))  
sim.out ([TXT](/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/assignments/simout.txt))  
  
Result of complete-link clustering to the 2-cluster level.  
cluster1 ([TXT](/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/assignments/cluster1.txt))  
cluster2 ([TXT](/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/assignments/cluster2.txt))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Homework 4 ([PDF]({{< baseurl >}}/resources/hw4))
{{< tdclose >}}
{{< tdopen >}}
poscounts.gz ([GZ]({{< baseurl >}}/resources/poscounts)) (The GZ file contains: poscounts.txt.)  
wsj.19-21.test ([TXT](/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/assignments/wsj1921test.txt))  
  
_Extra Materials_  
  
A package containing the scripts that were used to generate the poscounts.gz corpus. We are providing this code in case you are curious about the data generation. For the purposes of the problem set, however, please use the poscounts.gz training corpus to ensure that your results comply with the reference implementation.  
ft.tar.tar ([TAR - 2.5 MB]({{< baseurl >}}/resources/fttar))  
  
Development data for testing your tag-trigram probabilities; tritest contains tag trigrams, while tritest.probs contains the corresponding probabilities.  
tritest ([TXT](/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/assignments/tritest.txt))  
tritest.probs ([TXT](/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/assignments/tritestprobs.txt))  
  
Development data for testing your Viterbi tag assignments. The simplesents file contains about 530 simple sentences that admit relatively few possible tag assignments. The simplesents.bf\_tagged file contains optimal tag assignments and log-probabilities as discovered by brute-force enumeration. The first element in every line of simplesents.bf\_tagged gives the log-probability of the best tagging, and the rest of the line gives the tag assignment itself.  
simplesents ([TXT](/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/assignments/simplesents.txt))  
simplesents.bf\_tagged ([TXT](/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/assignments/simplesentsbf_tagged.txt))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Homework 5 ([PDF]({{< baseurl >}}/resources/hw5))
{{< tdclose >}}
{{< tdopen >}}
_Resources_  
  
[BoosTexter](http://rob.schapire.net/) - The download page for the BoosTexter binaries. If you get an error message, try reloading the link. BoosTexter is UNIX®-based, so if you want to run it in Windows, you will need to get a UNIX® shell such as [Cygwin](http://www.cygwin.com/) or [U/Win](http://www.research.att.com/sw/tools/uwin).  
  
[Penn Treebank Tagset](https://www.ling.upenn.edu/courses/Fall_2003/ling001/penn_treebank_pos.html) - Descriptions of the Penn part-of-speech tags. NB: When you are determining the plurality of a noun phrase, you will find that the last tag is not always a noun-type tag. Use the following rule to determine the plurality of these other parts of speech:  
Plural: CD, JJP, SYM  
Singular: DT, JJ, RB, VBG, WDT  
  
_Datasets_  
  
Sentence pairs with coreference annotations.  
coref\_samples.train ([TXT](/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/assignments/coref_samplestrain.txt))  
coref\_samples.test ([TXT](/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/assignments/coref_samplestest.txt))  
  
BoosTexter .names template for feature generation. Please adhere to this template to ensure that your features conform to the reference results.  
coref.names ([TXT](/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/assignments/corefnames.txt))  
  
Reference features for the first 30 sentence pairs in coref\_samples.train. The feature vectors were generated in a left-to-right postorder traversal of the noun phrases in a given sentence pair; e.g.  
\[\[ \[\[ 1 \]\] 2 \]\] \[\[ 3 \]\] \[\[ 4 \]\] \[\[ \[\[ 5 \]\] \[\[ \[\[ 6 \]\] 7 \]\] 8 \]\]  
first30.data ([TXT](/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/assignments/first30data.txt))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Homework 6 ([PDF]({{< baseurl >}}/resources/hw6))
{{< tdclose >}}
{{< tdopen >}}
corpus.de.gz ([GZ]({{< baseurl >}}/resources/corpusde)) (The GZ file contains: corpus.de.txt.)  
corpus.en.gz ([GZ]({{< baseurl >}}/resources/corpusen)) (The GZ file contains: corpus.en.txt.)  
  
_Datasets_  
  
A set of words and their associated translation probabilities. The output file is formatted as a series of lines, where each line contains a number of (German word, translation probability) pairs, all tokens separated by spaces.  
devwords ([TXT](/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/assignments/devwords.txt))  
devwords.out ([TXT](/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/assignments/devwordsout.txt))  
  
A set of words for which you must provide output probabilities. Please provide a file testwords.out with the same format as devwords.out above.  
testwords ([TXT](/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/assignments/testwords.txt))
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}