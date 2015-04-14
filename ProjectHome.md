This is the project page for RO, the new OBO Relations Ontology. This ontology replaces [OBO\_REL](http://obofoundry.org/ro).

## Summary ##

RO is a collection of relations intended primarily for standardization across ontologies in the [OBO Foundry](http://obofoundry.org) and wider OBO library. It incorporates [core](ROCore.md) upper-level relations such as [part of](http://purl.obolibrary.org/obo/BFO_0000050) as well as biology-specific relationship types such as [develops from](http://purl.obolibrary.org/obo/RO_0002202).

See the site [Menu](Menu.md) for more info

## Download ##

Use the following URIs to download this ontology:

  * http://purl.obolibrary.org/obo/ro.owl
  * http://purl.obolibrary.org/obo/ro.obo

Note that the source ontology is OWL - the [OBO](OBOFormatUsersGuide.md) version may have less axioms. Another difference between the two formats is that the OWL makes use of imports, whereas everything is combined into one with the obo file.

## Browse ##

Currently the optimal way to browse RO is to use Protege and inspect ro.owl

See the [list of relations on OntoBee](http://www.ontobee.org/browser/term.php?o=RO&iri=http://www.w3.org/2002/07/owl%23ObjectProperty&graph=http://purl.obolibrary.org/obo/merged/RO) -- note that sometimes OntoBee fails to display the full hierarchy

## Mail List ##

  * main: http://lists.sourceforge.net/lists/listinfo/obo-relations
  * mirror: http://groups.google.com/group/obo-relations


## Examples of usage ##

See [UsageExamples](UsageExamples.md)

## Requesting new relations ##

Use [obo-relations issue tracker](http://code.google.com/p/obo-relations/issues/list) and/or the obo-relations mail list.

## Shortcut Relations ##

RO includes a number of _macro_ or _shortcut_ relations. E.g

  * [capable of](http://purl.obolibrary.org/obo/RO_0002215)
  * [has postynaptic terminal in](http://purl.obolibrary.org/obo/RO_0002110)

For more information, see [ShortcutRelations](ShortcutRelations.md)

## Modularization ##

RO combines multiple relations from different biological sub-domains into one ontology. Sometimes these relations are very specialized and of limited use outside that domain. For more on extracting specific modules, see:

See [ROModules](ROModules.md).

## RO replaces OBO\_REL ##

The predecessor of RO was OBO\_REL. Many of the relations in OBO\_REL have been ceded to BFO. See [DifferencesWithOldRO](DifferencesWithOldRO.md)

## Coordination with BFO ##

For details on how RO coordinates with BFO, See [ROAndBFO](ROAndBFO.md).