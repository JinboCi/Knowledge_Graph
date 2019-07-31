1. In the last example of Filters.pdf, what should I do if I want to print the name out rather than URI?
- hahaha, answered in Optional.pdf
2. In this block of code:
PREFIX foaf: <http://xmlns.com/foaf/0.1/>
PREFIX vCard: <http://www.w3.org/2001/vcard-rdf/3.0#>
SELECT ?name
WHERE
{
{ [] foaf:name ?name } UNION { [] vCard:FN ?name }
}
what does "[]" means?
