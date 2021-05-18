# Ontology-exercise

Three .owl files are included in the repository

1/ "std_ontology.owl" was the first one created
   It was done on the day right after the class, using as many unique Protégé object properties as "arrows" in the diagram.
   However, Protégé does not infer anything from this ontology, which seems logical to us given that all classes are disjoints and each object property is used only once and only    between two classes.

2/ "new_try.owl" is actually our last try
   It has object properties linking more that two classes, and a better understanding of the use of "some" and "only". Because of this, we thought inferences would appear, such as
   "class Organisation_normalisation" is Equivalent to "class Consortium".
   However, this is not the case and once more, as soon as we are done entering all the assertions according to the diagram, Protégé stops inferring anything.
   This ontology file is the one corresponding exactly to the diagram.
   
3/ "ces_projet_2021.owl" is an unfinished try
    It is here only to demonstrate how Protégé can infer things on our model. However, in this file the implementation is incomplete. As soon as we complete the implementation   
    according to the model (resulting in one or the other of the two other .owl files included) Protégé stops finding any inference.
    Here, it infers (wrongly, but the model is incomplete) that the classes "Commission_nationale" and "Organisation" are subclasses of the class "Groupe_travail"

Conclusion:
There is obviously something missing in the model, or in its implementation in Protégé. 
The model was validated during the class, and the "std_ontology.owl" was created according to the directives given during the class as well.
We made further tries (not all reported here) and "new_try.owl" is reflecting the changes after the clarification given on the use of "some"  and "only", and succeed in using some object properties linking more than one single object to another single object.

Further notes : 
- All three files need to be opened in english to be readable, and are readable with Webprotege by selecting "en" at the creation of the project using the .owl file.
- The diagram was designed and uploaded on GitHub using a very nice onliine tool : app.diagrams.net



