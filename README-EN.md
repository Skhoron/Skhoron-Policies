# Skhoron Policies

A single source of rules, templates, and processes for projects in the Skhoron ecosystem.

Important: this repository is an organizational source of templates and rules. It does not replace legal texts that must be located in the root of the relevant project. Each specific project is governed by its own LICENSE, SECURITY.md, CONTRIBUTING.md, and other published documents.

Structure
Root
CODE_OF_CONDUCT.md — rules of conduct for contributors.
CLA.md — the historical filename for the DCO policy; in fact, the document describes the Developer Certificate of Origin.
FUNDING.yml — an example GitHub Sponsors configuration.
TEMPLATE/ — document templates for new projects. Currently, the collection contains only LICENSE.template.md (Apache-2.0); for projects with a different license (MIT, AGPL-3.0, MPL-2.0, etc.), use the official license text from its source.
Project directories
The skhoron-<name>/ directories contain decisions and open issues related to a specific project. These notes do not replace the project's legal documents.

Licenses
A license is selected separately for each project. It must not be assumed that all Skhoron projects automatically use the same license.

Project	License	Status
Skhoron-Files (Skhoron-Fails)	Apache-2.0	decided
About-me	AGPL-3.0	decided
Skhoron-VPF	MIT	decided
Skhoron-Vault	Apache 2.0	decided
Skhoron-Passgen	Apache 2.0	decided
Skhoron-Acro	GPL	decided
skhoron-notes	Apache 2.0	decided
Skhoron-Quark	Apache 2.0	decided
Skhoron-Sandbox	Apache 2.0	decided
Skhoron-Safeguard	Apache 2.0	decided
Skhoron-2FA	Apache 2.0	decided
Skhoron-Transport-Protocol	GPLv3	decided
Skhoron-SrcBox	BSD-3-CLAUSE	decided
Skhoron-PwGen	BSD-3-CLAUSE	decided
Pget	MIT	decided
Skhoron-Maps	MPL 2.0	decided
Skhoron-Chitin	Apache 2.0	decided
Skhoron-Matrix	AGPLv3	decided
Policies	No License	decided
The table reflects the state of affairs as of the last update to this file and must be maintained manually. If a project receives a different license in the future (or a license is selected for the first time), its entry in this table must be updated.

Changing the license
The author/copyright holder may change the license for future versions if they have the necessary rights to do so. Such a change does not, by itself, revoke rights that have already been granted to users under previously published versions.

This does not mean that an author can unilaterally change the license for code whose copyright they do not own.

Forks and branding
Forking, modifying, and distributing are permitted within the terms of the specific project's license.

Rights to code and rights to trademarks/names are different things. Permission to use the code does not automatically grant permission to use the Skhoron name or logo in a way that creates the impression of an official project.

Before publishing
A project must not contain unfilled legal or contact placeholders. The minimum checklist:

LICENSE contains the complete text of the selected license;
README specifies the same license;
CONTRIBUTING.md is consistent with the DCO;
CODE_OF_CONDUCT.md contains a real means of contact;
SECURITY.md contains a working security contact or enabled GitHub Security Advisories;
links lead to existing pages;
document versions and dates are current.
Rule in case of discrepancies
For the licensing terms of a specific version of the code, the primary document is the LICENSE distributed with that version. This repository cannot, by itself, change the terms of an already published version.