---
title: Digital Object Identifiers (DOIs)
has_children: false
nav_order: 11
---

# Digital Object Identifier (DOI) Service

## What is a DOI?

A **[Digital Object Identifier (DOI)](https://en.wikipedia.org/wiki/Digital_object_identifier)** is an unique, alphanumeric string of characters used to persistently identify an electronic object, such as an article, book, or dataset. The standard is managed by the **[International DOI Foundation](http://www.doi.org/index.html)**.

A DOI is not a URL, but provides a persistent link to the digital item on the web using a resolver service. Adding a DOI to the resolver's URL will redirect a browser to the current landing page describing the digital object. This helps ensure your citation will not become a broken link.

For example, the DOI <span style="color: red;">`10.1002/jwmg.72`</span> can be resolved at the URL **[http://doi.org/10.1002/jwmg.72](http://doi.org/10.1002/jwmg.72)**

## Why use a DOI?

While the use of DOI is common for academic journal articles, there is a growing demand to issue DOI for datasets. Potential benefits include:

- Greater exposure and discoverability - DOI metadata is ingested by search engines and indexes.
- Increased citation - authoritative references to the object are simplified.
- Better measurement of impact - DOI citations can be consistently tracked in scholarly networks.
- Funding requirements - agency guidelines may require a persistent identifier to meet data sharing policies.

## Can you issue me a DOI?

Yes!

If you have a dataset or other digital object that would benefit from a persistent identifier, the University of Idaho Library is able to issue DOI.

DOI are subject to these guidelines:

1. The digital object is publicly available on the web and will be managed for long term persistent access. This assumes a stable repository with appropriate capacity to store the items.
2. You will provide quality metadata with enough information for the public to understand and make "meaningful use" of the digital object.
3. The DOI will reference an up-to-date landing page with full information about the digital object, rather than a direct download link to the object.
4. If your dataset is hosted in the **[VERSO](https://verso.uidaho.edu)** data repository, these criteria are met! For questions or other use cases, please contact **[Jeremy Kenyon](mailto:jkenyon@uidaho.edu)** to obtain a DOI.

## Required metadata

At minimum DOI require the mandatory fields of the **[DataCite Metadata Schema](http://schema.datacite.org/)**. This includes:

- **Location URL**: The current location (URL) of the identified object, preferably a landing page with full descriptive information and access to the object.
- **Creator**: The main researchers involved in producing the data, or the authors of the publication in priority order. Each name may be a corporate, institutional, or personal name. In personal names list family name before given name, as in: Shakespeare, William. Non-roman names should be transliterated. Feel free to ask about the best practice for doing this.
- **Title**: A name or title by which the data or publication is known
- **Publisher**: A holder of the data (e.g., an archive) or the institution which submitted the work. In the case of datasets, the publisher is the entity primarily responsible for making the data available to the research community.
- **Publication Year**: The year when the data was or will be made publicly available. If an embargo period is in effect, use the year when the embargo period ends.
- **Resource Type**: The general type of the data: Audiovisual, Collection, Dataset, Event, Image, InteractiveResource, Model, PhysicalObject, Service, Software, Sound, Text, Workflow, Other.

## How to cite with a DOI

Citing datasets is essential for reproducible research, ensuring sources can be validated, creators get credit, and impact can be measured. DOI help create unambiguous citations to datasets. As with traditional resources, data citations should include the information necessary to identify and locate the source, generally including Creator, Publication Year, Title, Publisher, and Identifier.

For example:

- Engott, J.A., 2015, Mean annual water-budget components for the Island of Oahu, Hawaii, for average climate conditions, 1978-2007 rainfall and 2010 land cover: U.S. Geological Survey data release, [http://doi.org/10.5066/F7XP72ZX](http://doi.org/10.5066/F7XP72ZX)


## Example dataset with a DOI

The basic life cycle for a DOI is outlined below. Most of these steps are completed by the DOI service or repository stewards, but illustrate how a DOI works.

1. Researchers deposit a dataset in the **[VERSO](https://verso.uidaho.edu)** data repository.
2. VERSO registers the metadata and current landing page with DataCite, which automatically issues a unique identifier `doi:10.60841/000000269`. The DOI consists of the VERSO prefix (10.60841), plus a unique string called the remainder (000000269). The complete information recorded by DataCite is represented at the Identifier Details page.
3. DataCite registers the information with resolver services. The identifier can then be resolved by adding it to the DOI URL or by using other resolver services. To cite the data set, use the link: http://doi.org/10.60841/000000269
4. Going forward, the VERSO repository will update the Location URL in DataCite as needed ensuring that existing citations will not be broken, even if the web accessible location changes. Remember, DOIs are not magic! Ensuring the DOI is persistent requires active maintenance by the steward of the digital item.