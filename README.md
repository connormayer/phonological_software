# Phonological software repository

A repository containing links to useful phonological software. The goal is to provide a one-stop shop for phonology-related software.

## How to contribute

### Guidelines

* Software described in published papers or conference proceedings is preferred
* Please provide a link to an implementation. This could be a GitHub repo or some other website hosting the code.
* Please place your resource in the appropriate section. If there is no topic you feel adequately describes your software, you can add a new topic or subtopic.
* Please indicate which language the program is written in.

### Adding a new resource

The best way to add a new resource is to create a pull request via the GitHub user interface.

1. Click on the edit button in the top right corner of this file.

2. This will let you edit the Markdown of the file. See [here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) for information about Markdown syntax. Add your entry.

3. Click the "Preview changes" tab at the top of the page to verify your entry is formatted correctly.

4. Once you're happy with your changes, scroll to the buttom of the page to the box labeled "Commit changes". Add a name for your proposed change and a description if you wish. Select ""Create a new branch for this commit and start a pull request" and then click "Propose file change".

If you are uncomfortable using GitHub, you can email cjmayer@uci.edu with your proposed changes.


## Optimality theory

### General
* [OTSoft](https://linguistics.ucla.edu/people/hayes/otsoft/): A Windows program that implements several constraint ranking/weighting procedures, as well as other useful procedures.
* [OT-Help](https://people.umass.edu/othelp/): Comparable to OTSoft but works on Mac. 

### Maxent OT
* [Hayes and Wilson learner](https://linguistics.ucla.edu/people/hayes/Phonotactics/index.htm): A Java program that learns MaxEnt phonotactic grammars from positive data.
* [maxent.ot](https://github.com/connormayer/maxent.ot): An R package for fitting and evaluating MaxEnt OT grammars.
* [Maxent Grammar Tool](https://linguistics.ucla.edu/people/hayes/MaxentGrammarTool/): A Java tool for fitting MaxEnt grammars.

## Phonology-specific learners
This includes resources that are designed to learn or model specific types of phonological phenomena, such as features or classes. 

### Phonological class learning
* [Distributional learner](https://github.com/connormayer/distributional_learning): A Python program that learns phonological classes from distributional information.

### Phonological feature learning
* [Featurizer](https://github.com/connormayer/featurizer): A Python program that learns phonological feature systems from a set of input classes.

### Phonotactic learning
* [Phonotactic Language Model](https://github.com/MaxAndrewNelson/Phonotactic_LM): A Python program that learns phonotactics using recurrent neural networks.

## Formal language phonology
This includes resources that are focused on learning or modeling general formal grammars (FSAs, FSTs, etc.). These grammars are not designed for any individual phonological phenomenon (such as feature learning or phonotactic learning). They can be freely adapted or used for these more specific tasks.

### General toolkits
* [BMRS](https://github.com/jhdeov/BMRS): A Python implementation for Boolean Monadic Recursive Schemes, essentially a logic-based transducer. 
* [Language Toolkit](https://github.com/vvulpes0/Language-Toolkit-2): A Haskell library and DSL for constructing, factoring, and learning subregular stringsets.
* [SigmaPie](https://github.com/alenaks/SigmaPie): A Python library for subregular (SL, TSL, MTSL, SP) and subsequent (OSTIA) learning algorithms. Can do scanning, sample generation, and negative-positive grammar conversion.
### Individual learners
* [2IMTSL](https://github.com/alenaks/2IMTSL): A Python implementation for learning MITSL(2,2) grammars. 
* [OSTIA](https://github.com/alenaks/OSTIA): A Python implementation for the OSTIA learning algorithm.
* [pTSL](https://github.com/connormayer/pTSL): A Python program for implementing and fitting probabilistic tier-based strictly local grammars.

## Data repositories
This includes resources that collect cross-linguistic phenomena alongside either a) formal grammars or b) enough annotation that can facilitate in-depth phonological analyses

* [DoReCo](https://doreco.huma-num.fr/): A cross-linguistic speech corpus that is word-aligned and phone-aligned. It can be used as a general dataset for corpus phonetics
* [OpenSLR](https://openslr.org/index.html): A cross-linguistic directory of open-access speech corpora. 
* [Open Speech Corpora](https://github.com/coqui-ai/open-speech-corpora): A GitHub repo that is a directory to open-access speech corpora. 
* [RedTyp](https://github.com/jhdeov/RedTyp): A cross-linguistic database of reduplication patterns, along with a finite-state implementation (for 2-way FSTs), incomparable to the [Graz Database on Reduplication](http://reduplication.uni-graz.at/).
* [StressTyp](http://st2.ullet.net/?): A cross-linguistic database of stress patterns, along with a finite-state implementation (FSAs). 
* [UCLA Phonetics Lab Archive](archive.phonetics.ucla.edu/): A cross-linguistic database of recoreded word lists and other material. 
* [WikiPron](https://github.com/CUNY-CL/wikipron/): A cross-linguistic database of IPA transcriptons that are extracted from Wiktionary. 

## Speech corpus tools
This includes resources that you can use to work on a speech corpus. 

### Forced alignment
Forced alignment tools can speed up your annotation time. Different alignment tools offer pre-existing alignment models for certain languages, and some can let you train your own model on a new language. To learn more about a specific aligner, refer to the respective repo. 

* [Montreal Forced Aligner](https://montreal-forced-aligner.readthedocs.io/en/latest/) with [tutorials](https://montreal-forced-aligner.readthedocs.io/en/latest/). 

