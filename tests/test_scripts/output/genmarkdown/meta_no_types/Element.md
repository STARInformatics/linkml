
# Class: Element


a named element in the model

URI: [linkml:Element](https://w3id.org/linkml/Element)


![img](http://yuml.me/diagram/nofunky;dir:TB/class/[TypeDefinition],[SubsetDefinition],[SlotDefinition],[SchemaDefinition],[LocalName],[Extension],[Extensible],[Example],[EnumDefinition],[SubsetDefinition]<in_subset%200..*-%20[Element&#124;name:string;id_prefixes:ncname%20*;definition_uri:uriorcurie%20%3F;aliases:string%20*;mappings:uriorcurie%20*;description:string%20%3F;deprecated:string%20%3F;todos:string%20*;notes:string%20*;comments:string%20*;from_schema:uri%20%3F;imported_from:string%20%3F;see_also:uriorcurie%20*;exact_mappings:uriorcurie%20*;close_mappings:uriorcurie%20*;related_mappings:uriorcurie%20*;narrow_mappings:uriorcurie%20*;broad_mappings:uriorcurie%20*;deprecated_element_has_exact_replacement:uriorcurie%20%3F;deprecated_element_has_possible_replacement:uriorcurie%20%3F],[Example]<examples%200..*-++[Element],[AltDescription]<alt_descriptions%200..*-++[Element],[LocalName]<local_names%200..*-++[Element],[SlotDefinition]-%20range%200..1>[Element],[Element]uses%20-.->[Extensible],[Element]uses%20-.->[Annotatable],[Element]^-[TypeDefinition],[Element]^-[SubsetDefinition],[Element]^-[SchemaDefinition],[Element]^-[EnumDefinition],[Element]^-[Definition],[Definition],[Annotation],[Annotatable],[AltDescription])

## Uses Mixins

 *  mixin: [Extensible](Extensible.md) - mixin for classes that support extension
 *  mixin: [Annotatable](Annotatable.md) - mixin for classes that support annotations

## Children

 * [Definition](Definition.md) - base class for definitions
 * [EnumDefinition](EnumDefinition.md) - List of values that constrain the range of a slot
 * [SchemaDefinition](SchemaDefinition.md) - a collection of subset, type, slot and class definitions
 * [SubsetDefinition](SubsetDefinition.md) - the name and description of a subset
 * [TypeDefinition](TypeDefinition.md) - A data type definition.

## Referenced by class

 *  **[SlotDefinition](SlotDefinition.md)** *[range](range.md)*  <sub>OPT</sub>  **[Element](Element.md)**

## Attributes


### Own

 * [aliases](aliases.md)  <sub>0..*</sub>
     * range: [String](String.md)
 * [alt_descriptions](alt_descriptions.md)  <sub>0..*</sub>
     * range: [AltDescription](AltDescription.md)
 * [broad mappings](broad_mappings.md)  <sub>0..*</sub>
     * Description: A list of terms from different schemas or terminology systems that have broader meaning.
     * range: [Uriorcurie](Uriorcurie.md)
 * [close mappings](close_mappings.md)  <sub>0..*</sub>
     * Description: A list of terms from different schemas or terminology systems that have close meaning.
     * range: [Uriorcurie](Uriorcurie.md)
 * [comments](comments.md)  <sub>0..*</sub>
     * Description: notes and comments about an element intended for external consumption
     * range: [String](String.md)
     * in subsets: (owl)
 * [definition_uri](definition_uri.md)  <sub>OPT</sub>
     * Description: the "native" URI of the element
     * range: [Uriorcurie](Uriorcurie.md)
 * [deprecated](deprecated.md)  <sub>OPT</sub>
     * Description: Description of why and when this element will no longer be used
     * range: [String](String.md)
 * [deprecated element has exact replacement](deprecated_element_has_exact_replacement.md)  <sub>OPT</sub>
     * Description: When an element is deprecated, it can be automatically replaced by this uri or curie
     * range: [Uriorcurie](Uriorcurie.md)
 * [deprecated element has possible replacement](deprecated_element_has_possible_replacement.md)  <sub>OPT</sub>
     * Description: When an element is deprecated, it can be potentially replaced by this uri or curie
     * range: [Uriorcurie](Uriorcurie.md)
 * [description](description.md)  <sub>OPT</sub>
     * Description: a description of the element's purpose and use
     * range: [String](String.md)
     * in subsets: (owl)
 * [exact mappings](exact_mappings.md)  <sub>0..*</sub>
     * Description: A list of terms from different schemas or terminology systems that have identical meaning.
     * range: [Uriorcurie](Uriorcurie.md)
 * [examples](examples.md)  <sub>0..*</sub>
     * Description: example usages of an element
     * range: [Example](Example.md)
     * in subsets: (owl)
 * [from_schema](from_schema.md)  <sub>OPT</sub>
     * Description: id of the schema that defined the element
     * range: [Uri](Uri.md)
 * [id_prefixes](id_prefixes.md)  <sub>0..*</sub>
     * Description: the identifier of this class or slot must begin with one of the URIs referenced by this prefix
     * range: [Ncname](Ncname.md)
 * [imported_from](imported_from.md)  <sub>OPT</sub>
     * Description: the imports entry that this element was derived from.  Empty means primary source
     * range: [String](String.md)
 * [in_subset](in_subset.md)  <sub>0..*</sub>
     * Description: used to indicate membership of a term in a defined subset of terms used for a particular domain or application (e.g. the translator_minimal subset holding the minimal set of predicates used in a translator knowledge graph)
     * range: [SubsetDefinition](SubsetDefinition.md)
 * [local_names](local_names.md)  <sub>0..*</sub>
     * range: [LocalName](LocalName.md)
 * [mappings](mappings.md)  <sub>0..*</sub>
     * Description: A list of terms from different schemas or terminology systems that have comparable meaning. These may include terms that are precisely equivalent, broader or narrower in meaning, or otherwise semantically related but not equivalent from a strict ontological perspective.
     * range: [Uriorcurie](Uriorcurie.md)
 * [name](name.md)  <sub>REQ</sub>
     * Description: the unique name of the element within the context of the schema.  Name is combined with the default prefix to form the globally unique subject of the target class.
     * range: [String](String.md)
     * in subsets: (owl)
 * [narrow mappings](narrow_mappings.md)  <sub>0..*</sub>
     * Description: A list of terms from different schemas or terminology systems that have narrower meaning.
     * range: [Uriorcurie](Uriorcurie.md)
 * [notes](notes.md)  <sub>0..*</sub>
     * Description: editorial notes about an element intended for internal consumption
     * range: [String](String.md)
     * in subsets: (owl)
 * [related mappings](related_mappings.md)  <sub>0..*</sub>
     * Description: A list of terms from different schemas or terminology systems that have related meaning.
     * range: [Uriorcurie](Uriorcurie.md)
 * [see_also](see_also.md)  <sub>0..*</sub>
     * Description: a reference
     * range: [Uriorcurie](Uriorcurie.md)
     * in subsets: (owl)
 * [todos](todos.md)  <sub>0..*</sub>
     * Description: Outstanding issue that needs resolution
     * range: [String](String.md)

### Mixed in from annotatable:

 * [annotations](annotations.md)  <sub>0..*</sub>
     * Description: a collection of tag/text tuples with the semantics of OWL Annotation
     * range: [Annotation](Annotation.md)

### Mixed in from extensible:

 * [extensions](extensions.md)  <sub>0..*</sub>
     * Description: a tag/text tuple attached to an arbitrary element
     * range: [Extension](Extension.md)

## Other properties

|  |  |  |
| --- | --- | --- |
| **See also:** | | https://en.wikipedia.org/wiki/Data_element |

