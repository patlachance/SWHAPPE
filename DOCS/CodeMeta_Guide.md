Property | Value | Type | Description
------------ | ------------- | ------------- | -------------
identifier | TBD | PropertyValue or URL | *a unique identifier* The identifier property represents any kind of identifier for any kind of Thing, such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links. See background notes for more details.
applicationCategory (*domain*) | Signal processing  | Text or URL | Type of software application, e.g. ‘Game, Multimedia’.
name | Softi | Text | The name of the software.
description |  This short FORTRAN routine smoothes a digitized curve.  | Text | *a brief description of the software* A description of the item.
keywords | Numerical Analysis, Smoothening, FORTRAN, CEP | Text | Keywords or tags used to describe this content. Multiple entries in a keywords list are typically delimited by commas.
dateCreated (*Date of creation*)  | terminus post quem: 12/02/1968  | Date or DateTime | *developement start date* The date on which the CreativeWork was created or the item was added to a DataFeed.
datePublished (*Date of publication*) | TBD | Date | *publication date* Date of first broadcast/publication.
releaseNotes *comments* | NAv | Text or URL | *release notes* Description of what changed in this version.
referencePublication *References* | TBD | |
*project* | TBD | Text or URL | *maybe the software is part of some project*
relatedLink (*Related links*) | TBD | URL | *\[related links\]* A link related to this object, e.g. related web pages.
funding | TBD  | Text | Funding source (e.g. specific grant)
programmingLanguage  | CEP Fortran | ComputerLanguage or Text | *main programming language* The computer programming language.
codeRepository | TBD | URL | *URL to related resources* Link to the repository where the un-compiled, human readable code and related code is located (SVN, GitHub, CodePlex, institutional GitLab instance, etc.). **Self-referencial?**
*Platform/OS* targetProduct | TBD | SoftwareApplication | Target Operating System / Product to which the code applies. If applies to several versions, just the product name can be used.
softwareRequirements | TBD | SoftwareSourceCode |*\[dependencies and other requirements\]* Required software dependencies
softwareVersion | TBD | Text | Version of the software instance.
developmentStatus | TBD | Text | Description of development status, e.g. Active, inactive, suspended. See repostatus.org
license | TBD | CreativeWork or URL | *info about the runtime environment* A license document that applies to this content, typically indicated by URL.
*Runtime platform* runtimePlatform | TBD | Text | Runtime platform or script interpreter dependencies (Example - Java v1, Python2.3, .Net Framework 3.0). Supersedes runtime.
author | Antonina (Tonina) Starita | Organization or Person | *\[authors\]* The author of this content or rating. Please note that author is special in that HTML 5 provides a special mechanism for indicating authorship via the rel tag. That is equivalent to this and may be used interchangeably.
*Developers* | NAp | Person | *\["other contributors and mantainers"\]* **maintainer, contributor?**
affiliation | IEI-CNR | Text **Why not Organization?** | An organization that this person is affiliated with. For example, a school/university.
