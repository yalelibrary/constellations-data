# Constellations Data
## Description
This repository contains data related to the Constellations project.

## Wikidata Lists
These files can be edited to exclude images, exclude properties, and rename properties.
- [all_properties_list.csv](wikidata-lists/all_properties_list.csv): A list of all the properties in wikidata for the all the entities. This list can be used to create `include_properties_list.csv` by removing the unwanted properties.
- [include_properties_list.csv](wikidata-lists/include_properties_list.csv): A list of all the properties to include in the site. This list can be created using `all_properties_list.csv` by removing the unwanted properties. You may also rename the properties in the `include_properties_list.csv` for any property id.

## Biographies
The biographies are in [biographies/](biographies).<br />
(e.g. [biographies/Q102293564.md](biographies/Q102293564.md))

They are in markdown format for easy and safe convertion to HTML.

## Publication Markdown
The publication markdown files are in [publications/](publications).<br />
(e.g. [publications/Q102293564.md](publications/Q102293564.md))

## Images
Images are in [images/](images).<br />
Only image files in that directory will be included. Wikidata references to images are not used.

## Property Value Overrides
The property value overrides are in [property-value-override/](property-value-override).<br />

(e.g. [property-value-override/Q102293564.json](property-value-override/Q102293564.json))

This will override the data in wikidata for a property.  If a value in wikidata is not wanted or needs to be edited it can be overridden using these files. To suppress a value for a specific entity, set the property to `null`. (You can suppress a property for all entities by removing it from the [include_properties_list.csv](wikidata-lists/include_properties_list.csv).)
