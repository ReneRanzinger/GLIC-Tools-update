# GLIC Tools update
This repository contains the standards and procedures for the update of the GLIC tools information page.

The past the GLIC [software webpage](https://glic.glycoinfo.org/software/) and [database](https://glic.glycoinfo.org/database/) list where manually curated. This caused a lot of manual work for the page provider and in addition lead to outdated entries.

The GLIC tools update strategy is designed to keep the GLIC webpage updated with the newest information about the available tools without requiring providers to have to send update information to GLIC or having to update the GLIC pages themselves. In addition the proposed mechanism can also be used by other projects such as [GlyGen](http://glygen.org/) or [ExPASy: SIB Bioinformatics Resource Portal](https://www.expasy.org/glycomics) to add the same tools to their webpages.

To update the GLIC webpage each tool provider has to provide information about his tool in the [tool information format](Tool-information-format) and register the tool information file in the [tools registry](Tool-registration-format) in this repository.

The GLIC webpage will run [regular updates](Update-strategy) of the tool information by pulling the newest information from the providers.
