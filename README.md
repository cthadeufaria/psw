# psw
## Repository to document FEUP software project studies
&nbsp;
# Exam #1 Notes

- ## OOP
	- Classes: nouns and noun phrases in stakeholders’ descriptions of the problem
	- Coad & Yourdon’s criteria: (T2 - 11-objects - by Steve Easterbrook, U. Toronto - only 1 to 8 Ficheiro / page 7)
        - Retained information: Will the system need to remember information about this
        class of objects?
        - Needed Services: Do objects in this class have identifiable operations that
        change the values of their attributes?
        - Multiple Attributes: If the class only has one attribute, it may be better
        represented as an attribute of another class
        - Common Attributes: Does the class have attributes that are shared with all
        instances of its objects?
        - Common Operations: Does the class have operations that are shared with all
        instances of its objects?

        &nbsp;
- ## UML Class Diagrams
	- Types of relationship (T2 - 11-objects - by Steve Easterbrook, U. Toronto - only 1 to 8 Ficheiro / page 9):
		- Association (defined with painted arrow)
			- multiplicity x..*
			- name and direction
			- role (inside association)
			- association can be a class (e.g. contract is an association class between buyer and house)
		- Aggregation and Composition (defined with painted diamond - composition - or blank diamond - aggregation)
			- Aggregation has a “Has-a” or “Whole/part” relationship
            - Composition is a strong form of aggregation that implies ownership 
		- Generalization (defined with blank arrow)
            - Capacity for inheritance (creation of superclass and its subclasses)
		- Dependency
            - ?
		- Realization
            - ?