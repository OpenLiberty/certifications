# certifications
This repository will be used to house the Jakarta EE TCK Results for the Certification Requests.
The TCK Results need to be in a publicly accessible website via a defined URL.
These TCK Results do not need to be accessible from the main [openliberty.io](https://openliberty.io) site.

## file format
The TCK Results will be asciidoc (TCKResults.adoc) files.
This format will allow for easy rendering onto the openliberty.io site.
Shortly after PRs are merged into this repo, the results will be accessible via https://openliberty.io/certifications/...

## directory structure
The following directory structure will be used to house these TCK Results:

```https://openliberty.io/certifications/jakartaee/<specification>/<specification version>/TCKResults```
For example,
```
https://openliberty.io/certifications/jakartaee/platform/8.0/TCKResults.html
https://openliberty.io/certifications/jakartaee/webprofile/8.0/TCKResults.html
https://openliberty.io/certifications/jakartaee/servlet/4.0/TCKResults.html
```
## TCKResults content
Reference the [sample TCKResults](./TCKResults.adoc) file for an example of the content.
