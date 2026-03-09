Dataset Schema

books.csv

book_id
book_name
canon_section
notes

passages.csv

book
chapter
verse
reference_id

cross_references.csv

source_book
source_chapter
source_verse
target_book
target_chapter
target_verse
relationship_type

themes.csv

book
chapter
verse
theme

video_index.csv

book
chapter
verse
video_title
video_url

commentary_nodes.json

node_id
book
chapter
verse
theme
commentary_text
author

cross_reference_network.csv

source_id
target_id
relationship_type
weight