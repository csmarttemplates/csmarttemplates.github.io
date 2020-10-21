# csmarttemplates.github.io

### CSmart Templates

This project contains reference templates for CSmart searches found at https://csmarttemplates.github.io/.
Search templates describe everything required to load information (lists of items) from a source into CSmart. CSmart supports loading items which have titles, urls, dates, prices, images such as RSS feeds or other formatted lists of data from web sources. This lets you access the information you want through a better user interface.

A search template describes specifies the following in JSON format:
- User Interface descriptors for search parameters panels ("fieldLayouts")
- Loading configuration descriptors ("loader")
- Metadata describing the template ("searchUUID", "name", etc.)
- Optional: Search Label UI for describing what to show for saved and recent searches ("searchLabelPatterns")
- Optional: Category descriptor for organizing saved searches by category. ("savedSearchCategories")
- Optional: Various structered lookup data objects in JSON format which may be referenced by tag name at the root level of the descriptor.

### User Interface descriptors


### Loading configuration descriptors
