# My Jekyll blog editor

Moving my website md blog editor here because this project could potentially grow complex.

My goal was to have a simple md editor that i could ise to automate jekyll layout formatting and naming conventions

Jupyter Notebook style was the inspiration behind this project.

The editor looks for the jekyll repository root, and then adds the posts
under _posts/ and the images under assets/images


!!!! This project is vibecoded and barely works, you should not trust it!

# TODO

- have a proper save system that doesn't crash if the article is big
- add a left side panel to quickly navigate thourgh the markers (titles, subtitles, images, etc)
- add a confirmation to save draft
- add delete posts from website with confirmations
- add math latex blocks
- add a small up/down page helper button
- add a confirmation button to delete a block
- add a TBA block to mark future completion
- add custom blocks support accepting a template maybe?
- maybe drop the jekyll and make this editor generate html files directly