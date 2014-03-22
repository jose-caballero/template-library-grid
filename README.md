template-library-grid
=====================

Template library for configuring EMI grid middleware services

EMI Services Validated (22/3/2014): WN, CREAM CE, BDII, DPM, UI (others coming soon)

Starting with this branch, the template layout has been slightly modified to be inline
with other template libraries. In particular the following namespaces (directories) have
been renamed:

- glite -> personality
- common -> feature
- machine-types -> machine-types/grid
- defaults/glite -> defaults/grid

Usually, only the machine-types change should have an impact on site templates.

Note: this branch requires Quattor 14.2.1 (YUM-based deployment only) and sl6.x OS templates.
