# Phrase Detectives Corpus 1.1

J. Chamberlain, M. Poesio and U. Kruschwitz
Release date: 1 May 2016

This is a corpus of 40 documents released from the main corpus of documents being annotated by 
the Phrase Detectives game (https://www.phrasedetectives.org).

Full documentation and preliminiary analysis of the data has been published in a paper at the
LREC16 conference entitled "Phrase Detectives Corpus 1.0: Crowdsourced Anaphoric Coreference"

Please review and cite the relevant papers if you use this resource:

Chamberlain, J., and Poesio, M., and Kruschwitz, U. (2016). Phrase Detectives Corpus 1.0. AnaWiki, University of Essex, ISLRN 955-898-221-547-9.

Chamberlain, J., and Poesio, M., and Kruschwitz, U. (2016). Phrase Detectives Corpus 1.0: Crowdsourced Anaphoric Coreference. 
In Proceedings of the 2016 Language Resources and Evaluation Conference (LREC'16).

Poesio, M., Chamberlain, J., Kruschwitz, U., Robaldo, L., and Ducceschi, L. (2013). Phrase Detectives: Utilizing collective intelligence for internet-scale language resource creation. 
ACM Transactions on Interactive Intelligent Systems.

Please report any errors or issues to jchamb@essex.ac.uk

# Document Guide

Source files are included in this corpus release including files appended:
* No appending or -no_headder = The original file
* .filtered = Coverted to an input format
* -masxml_xsd = Original MASXML file
* -masxml = File converted to MASXML format for the game
* -sgf = File converted to SGF format to imported into the game
* Export files are appended -game.

# Annotation Guide

\<PDante\>   
id = id of the markable  
visibility = whether the administrator marked this to be "hidden"  
start_chr = the markable span was edited and the new start character is this  
end_chr = the markable span was edited and the new end character is this  

\<anchor\>  
timestamp = time the annotation was created  
interface = interface the annotation was created on (0 = standalone PD, 1 = Facebook PD)  
mode = mode of annotation (a = annotation, v = validation, e = expert)  
agree = was this annotation in agreement with the interpretation  
annotation_time = time to create the annotation response from page load  
user_rating = rating of the user  
user_id = encrypted user_id  
type = interpretation type (DN = Discourse New, DO = Discourse Old, NR = Non-referring, PR = Property, SE = same entitiy)  
ante = antecedent markable id  
favoured = the expert indicates whether this is the best interpretation (y) or another might be better  

\<comment\>  
type/type_id = the type of error detected:  
1. not_selectable
2. out_of_context_window
3. parse_error
4. discourse_diexis
5. ambiguous
6. non_referring
7. nearest_mention_embedding
8. bridge
9. quantifier

# Change Log

23 April 2016: Files exported. Version 1.0 created.  
23 Jan 2017: space removed from "document list.xls" and replaced with underscore. Version 1.1 created  
23 Jan 2017: 5 documents from the GNOME corpora are removed  
23 Jan 2017: Files confirmed to validate against the masxmlpd.dtd  
15 Feb 2017: Intermediate source files removed  
