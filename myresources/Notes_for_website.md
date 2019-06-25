# To add new group members
* Copy an existing entry, reformat


# To add new publications 
* add entry to 'mynewbibs.bib' file. Include abstract. Can do that by pulling website article from zotero or through myncbi.
* Run the academic tool for publications: https://sourcethemes.com/academic/docs/managing-content/
* Make sure folder is not the actual website since we don't want existing pubs overwritten, otherwise they'll loose their special formatting.
* Copy the new entries into the main /publication folder, adjust each index.md to include citation/pdf/pub type
* Rename bib files to cite.bib
* My custom publication types are in layouts/partials/pub_types/
publications.md in content/home describes the different types
To adjust labels/categories for publications, edit a layout file, then adjust numbers in publications:
https://github.com/gcushen/hugo-academic/issues/906



# To build site

run blogdown::build_site

# To deploy site
1. Run VPN
2. Mount network drive to \\128.192.39.205\ahgroup, connect with myid\ahandel
3. Copy everything in public/ to the main directory on the server



