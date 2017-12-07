# ExFlow Web for NAV - Release notes

Compared with version 3 the following features have been removed.
* Support for all IE versions <11 are dropped. 
* IE11 not supported in so-called **Compatibility mode**. 
* Coding favorites have been deprecated and will be replaced by enhanced line templates.
* IE11 on Windows Server using default security configuration where localStorage is disabled is not supported. 

The following features are currently under development.
* Boolean coding columns not supported.
* Paging/"scroll for more" in lookups (account, items, ..) are under development. 
* Line templates

## Releases

### Release 2017.20.0.0
2017-12-06 for on-prem and cloud

**New**
* Maintenance message (exflow.cloud/multitenant)
* Improves PDF image interaction
* New languages AU and NZ
* New versioning syntax Year.Release no.Custom no.Patch no
* Search and some inbox folders will sort based on Document Date or user preference rather than Due date.
* Adds support for NAV order fields and details.
* Adds inbox/search sorting by column click.
* Improves dashboard chart interaction.
* Adds line comments highlighting.
* Improves line and inbox paging and scrolling.
* Other UI improvements.
* Bug fixes.

### Release 19.0
Cloud only

**New**
* New versioning 2017.19.0.0 (experimental)
* Search and some inbox folders will sort based on Document Date or user preference rather than Due date.
* Adds support for NAV order fields and order details
* Adds inbox/search sorting by column click
* Improves dashboard chart interaction
* Adds line comments highlighting
* Improves line and inbox paging and scrolling
* Other UI improvements
* Bug fixes


### Release 17
2017-08-30 prerelease for on-prem

**New**
* Adds UI improvements.
* Improves client-side performance.
* Improves performance when reloading settings from Dynamics.
* Fixes a critical issue with PDF-files for D365
* Changes how the primary button work (the green one). The primary button will change from Approve (i.e. approve all lines) to Save/Send when the user makes a line approval decision.
* Bug fixes
