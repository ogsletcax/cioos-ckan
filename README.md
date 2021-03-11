# cioos-ckan reorg draft highlights

- more dockerish project structure
- The project is not a fork from ckan, ckan source code is downloaded in the ckan service dockerfile.
- one main plugin. Code from submodules can be moved there bit by bit when it makes sense.
- schema.xml moved to solr folder.
- harvester container generation slightly changed (using targets).
