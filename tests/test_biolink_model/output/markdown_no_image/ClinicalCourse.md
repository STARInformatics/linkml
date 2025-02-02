
# Class: ClinicalCourse


The course a disease typically takes from its onset, progression in time, and eventual resolution or death of the affected individual

URI: [biolink:ClinicalCourse](https://w3id.org/biolink/vocab/ClinicalCourse)


![img](http://yuml.me/diagram/nofunky;dir:TB/class/[QuantityValue],[OntologyClass],[Onset],[NamedThing],[ClinicalCourse&#124;name(i):label_type%20%3F;iri(i):iri_type%20%3F;source(i):label_type%20%3F]^-[Onset],[ClinicalAttribute]^-[ClinicalCourse],[ClinicalAttribute])

## Parents

 *  is_a: [ClinicalAttribute](ClinicalAttribute.md) - Attributes relating to a clinical manifestation

## Children

 * [Onset](Onset.md) - The age group in which (disease) symptom manifestations appear

## Referenced by class


## Attributes


### Inherited from clinical attribute:

 * [attribute➞name](attribute_name.md)  <sub>OPT</sub>
     * Description: The human-readable 'attribute name' can be set to a string which reflects its context of interpretation, e.g. SEPIO evidence/provenance/confidence annotation or it can default to the name associated with the 'has attribute type' slot ontology term.
     * range: [LabelType](types/LabelType.md)
 * [has attribute type](has_attribute_type.md)  <sub>REQ</sub>
     * Description: connects an attribute to a class that describes it
     * range: [OntologyClass](OntologyClass.md)
     * in subsets: (samples)
 * [has qualitative value](has_qualitative_value.md)  <sub>OPT</sub>
     * Description: connects an attribute to a value
     * range: [NamedThing](NamedThing.md)
     * in subsets: (samples)
 * [has quantitative value](has_quantitative_value.md)  <sub>0..*</sub>
     * Description: connects an attribute to a value
     * range: [QuantityValue](QuantityValue.md)
     * in subsets: (samples)
 * [iri](iri.md)  <sub>OPT</sub>
     * Description: An IRI for an entity. This is determined by the id using expansion rules.
     * range: [IriType](types/IriType.md)
     * in subsets: (translator_minimal,samples)
 * [source](source.md)  <sub>OPT</sub>
     * Description: a lightweight analog to the association class 'has provider' slot, which is the string name, or the authoritative (i.e. database) namespace, designating the origin of the entity to which the slot belongs.
     * range: [LabelType](types/LabelType.md)
     * in subsets: (translator_minimal)

## Other properties

|  |  |  |
| --- | --- | --- |
| **Exact Mappings:** | | HP:0031797 |

