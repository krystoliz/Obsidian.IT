THE STRUCTURE OF LANGUAGE
arrangement of words and phrases to create well formed sentences in a language
set of rules governing the structure and sentences, ensuring the words combine in a meaningful and grammatically correct ways

Understanding syntax is crucial for various NLP tasks - parsing, machine translation, question answering

Key Concepts:
- [[Constituents]] : Sentences are not merely linear string of words but acts as a single unit within the sentence.  'the black cat' can be broken down to smaller units, creating a tree-like structure. This concept is central to formal grammars like Context-Free Grammars (CFGs
- ![[Pasted image 20241126095426.png]])
- Grammatical Relations: Syntax define the relationships between words in a sentence such as object subject and modifier. this help determine the meaning of sentences and huide parsing algorithms in analysing sentence structure
- Word Classes [[POS Tagging]] : Categorizing words into respective parts of speech (nouns, vers, adjectives, adverbs) is fundamental un syntactic analysis. List of POS is provided by a tagsets including the Penn Treebank tagset
- Formal Grammars: math model describes the rule of language's syntax. CFG consists of rules that define how non-terminal symbols (phrases) can be expanded into sequences of terminal symbols ![[Pasted image 20241126103600.png]]
- **Parsing**: involves analyzing syntactic structure of sentence based on a given grammar. Parsing algorithms take a sentence as an input and output a parse tree represents hierarchical relationships between words
- Dependency parsing: alternative to constituency parsing, it focuses directly on the dependencies between words in a sentence (grammatical structure) , rather than building a phrase-structure tree. ![[Pasted image 20241126105422.png]]
“Man sits on the bench,” the word “**Man**” is the subject (the one doing something), “**sits**” is the main verb (what is being done), and “**bench**” is the object (on whom something is being done).

Dependency parsing focuses on the relationships between individual words rather than phrases or larger structures.

The basic idea is that every sentence has a subject, a verb, and an object. In present-day English, the typical word order for these elements is **subject-verb-object (SVO)**.


