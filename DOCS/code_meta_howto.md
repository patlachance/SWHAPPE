# A guide to fill in the codemeta entries.

## In the end, this may disappear, or left in the documentation. For the moment being, until we have a web form to enter them, this may be used to collect the values of the properties of interest.

Note: in the following table, I used *italic* to refer to terms or phrases used in the July 1st draft, when different from what used in the [CodeMeta Project]( https://codemeta.github.io/terms/). I used bold to point to issues, questions, choices...

Property | Value | Type | Description 
------------ | ------------- | ------------- | -------------
identifier | TBD | PropertyValue or URL | *a unique identifier* The identifier property represents any kind of identifier for any kind of Thing, such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links. See background notes for more details. 
applicationCategory (*domain*) | TBD | Text or URL | Type of software application, e.g. ‘Game, Multimedia’. 
name | TBD | Text | The name of the software. 
description | TBD | Text | *a brief description of the software* A description of the item.
keywords | TBD | Text | Keywords or tags used to describe this content. Multiple entries in a keywords list are typically delimited by commas.
dateCreated (*Date of creation*)  | TBD | Date or DateTime | *developement start date* The date on which the CreativeWork was created or the item was added to a DataFeed. 
datePublished (*Date of publication*) | TBD | Date | *publication date* Date of first broadcast/publication.
releaseNotes *comments* | TBD | Text or URL | *release notes* Description of what changed in this version. 
referencePublication *References* | TBD | ScholarlyArticle | *some ref to..?* An academic publication related to the software.
*project* | TBD | Text or URL | *maybe the software is part of some project*
relatedLink (*Related links*) | TBD | URL | *\[related links\]* A link related to this object, e.g. related web pages. 
funding | TBD | Text | Funding source (e.g. specific grant) 
programmingLanguage  | TBD | ComputerLanguage or Text | *main programming language* The computer programming language.
codeRepository | TBD | URL | *URL to related resources* Link to the repository where the un-compiled, human readable code and related code is located (SVN, GitHub, CodePlex, institutional GitLab instance, etc.). **Self-referencial?**
*Platform/OS* targetProduct | TBD | SoftwareApplication | Target Operating System / Product to which the code applies. If applies to several versions, just the product name can be used.
softwareRequirements | TBD | SoftwareSourceCode |*\[dependencies and other requirements\]* Required software dependencies
softwareVersion | TBD | Text | Version of the software instance.
developmentStatus | TBD | Text | Description of development status, e.g. Active, inactive, suspended. See repostatus.org
license | TBD | CreativeWork or URL | *info about the runtime environment* A license document that applies to this content, typically indicated by URL.
*Runtime platform* runtimePlatform | TBD | Text | Runtime platform or script interpreter dependencies (Example - Java v1, Python2.3, .Net Framework 3.0). Supersedes runtime.
author | TBD | Organization or Person | *\[authors\]* The author of this content or rating. Please note that author is special in that HTML 5 provides a special mechanism for indicating authorship via the rel tag. That is equivalent to this and may be used interchangeably.
*Developers* | TBD | Person | *\["other contributors and mantainers"\]* **maintainer, contributor?**
affiliation | TBD | Text **Why not Organization?** | An organization that this person is affiliated with. For example, a school/university.

