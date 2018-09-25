# Kantara Initiative Consent Receipt Specification
By: Andrew Hughes (andrewhughes3000@gmail.com), Chair of Kantara Initiative Leadership Council

Prepared for: W3C Workshop on Permissions and User Consent, San Diego, CA

Date: 2018-09-26

## Key points
* The [Kantara Consent Receipt specification](https://kantarainitiative.org/file-downloads/consent-receipt-specification-v1-1-0/) includes a JSON schema including fields defined for transactional information about when the user agreed (and to what), PII Controller contact, PII Principal info, privacy policy/statement link, details about the service offered and the purposes for data collection and processing.
* The specification is written for use in any jurisdiction - ISO terminology was used as a neutral basis
* A very simple demo of Consent Receipt interoperability between 4 products was presented at 2 recent events ([YouTube video here - 20 minutes run time](https://youtu.be/_bwXwnNaiZ8))
* The demo will add participant products and be enhanced over time and shown at industry events for the next couple years
* Further work planned on the specification includes: 
	* List of 'purposes' for specific industries, verticals or scenarios
	* API definition to support consent management platforms
	* Resolution of issues discovered during demo implementation
	* Adding structural elements to aid in parsing, caching and performance
	* Guidance and/or schema elements to aid in 'skinning' for different jurisdictions or languages
	* Investigation into use as a standard messaging format between backend systems that need to coordinate about user consent choices and changes 
* Kantara also has a WG developing 'best current practice' guidance on consent management practices

## Applicability to workshop agenda items
The work at Kantara appears most applicable to:

* Accountability and Provenance
* Timing and Duration
* Role of Platforms
* Interaction with Regulation and Policy

## Kantara Initiative work to date on Consent Management

### The [Kantara Initiative Consent & Information Sharing Work Group](https://kantarainitiative.org/confluence/display/infosharing/Home) published the [Kantara Consent Receipt Specification v1.1](https://kantarainitiative.org/file-downloads/consent-receipt-specification-v1-1-0/) on 2018-02-20

**Abstract:** A Consent Receipt is record of authority granted by a Personally Identifiable Information (PII) Principal to a PII Controller for processing of the Principal's PII. The record of consent is human-readable and can be represented as standard JSON. This specification defines the requirements for the creation of a consent record and the provision of a human-readable receipt. The standard includes requirements for links to existing privacy notices & policies as well as a description of what information has been or will be collected, the purposes for that collection as well as relevant information about how that information will be used or disclosed. This specification is based on current privacy and data protection principles as set out in various data protection laws, regulations and international standards.


Kantara presented a demonstration of Interoperable Consent Receipts at the [MyData 2018 conference](https://mydata2018.org/presentations/), Helsinki, August 28, 2018 in the [Consent In Action Session](https://mydata2018.org/sessions/consent-in-action/) there are excellent presentation videos - it's a very interesting conference.


Five active Consent & Information Sharing Work Group contributors invested developer time to create external Kantara-spec Consent Receipts for their products. These receipts were stored at a user-specified location, then viewed using a viewer created by OpenConsent. From start to finish, it took about 7 weeks to design, build, test and deliver.


The Consent Receipt [presentation was recorded](https://youtu.be/_bwXwnNaiZ8) and is posted (YouTube).
And the [slides can be downloaded](https://mydata2018.org/wp-content/uploads/sites/14/gravity_forms/19-eb584a27cf50606ce6d69843eecada2f/2018/08/mydata-2018-Kantara-consent-receipt-demo-v4.pptx) (pptx).


The demo was a hit - lots of conference delegates engaged with the presenters and we are hoping to see that interest result in more WG participants and more demo apps - and hopefully some of these in shipping products!

### The [Kantara Initiative Consent Management Solutions](https://kantarainitiative.org/confluence/display/consentmanagement) WG
The Consent Management Solutions (CMS) WG was created by the Kantara Initiative with the goal of providing more clarity and an industry-developed common practices guideline document around consent and privacy policies for use by organizations that manage and use large amounts of identity information and data.  The guidelines will be industry-vetted and lead to the formation of established standards and a certification program.

These work group outputs will help organizations meet new stringent regulations around personal identity and privacy information.  In keeping with Kantara’s mission of an open, participatory industry association model, all organizations and individuals involved in the consent, identity and privacy are welcome to join the CMS WG.


## About Kantara Initiative
*The Kantara Initiative is the global consortium improving trustworthy use of identity and personal data through innovation, standardization and good practice.*

[Kantara Initiative](https://kantarainitiative.org) is an ethics based, mission-led non-profit organization passionate about giving control of data back to people. It provides real-world innovation and development of specifications and conformity assessment programs for the digital identity and personal data ecosystems. Beyond its flagship eID-assisting Identity Assurance Trust Framework, developing initiatives including Identity Relationship Management, User Managed Access, Identities of Things, and the Consent Receipt specification, Kantara Initiative connects a global, open, and transparent leadership community. 