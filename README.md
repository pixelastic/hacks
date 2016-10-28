# hacks

This repo simply holds a list of hack ideas I have. I could dig back into this
list at a later time to find ideas for hackathons or rainy days.


## OCR Search

Google and Microsoft have great OCR APIs. I could find a dataset of images of
books, or any written material, push it to the API and then index the results
with Algolia. This would let me search into thousand of pages of any documents.

## Improved Velib

The Velib API is not great. It does not allow to search for stations based on
geo-loc, only list them. I could get the whole list of stations, and push them
into Algolia. By creating a small JS SDK I could leverage the Algolia API to
find the stations around me. I could even listen to changes of number of
available bikes through Streamdata and update Algolia in real time.

