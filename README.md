# Web-Scrapping-Archive-of-our-own-AO3-
Web Scripping pour AO3 based on following code : https://github.com/kenalba/ao3-scraper/blob/main/scraper.py



---

# What this code do ?

With this code you can append the following information from AO3 and put it into a data frame from a certain page to another

*  Story IDS of the work
*  Updated date of the work
*  Title and author of the work
*  Language of the work
*  Number of words in the work
*  Number of chapter in the work
*  Number of hits 
*  Requiered tags 
*  Additionnal tags

At the end of the code, you can find some graph and histogram on time and published work.

Then you'll have a section on how to find a tag in works if needed.



---
# How to use the code ?

**Step 1 : Set the parameters**

You want to append the data from wich page to wich page and from wich fandom.

If you want to append a lot of data use the **SAME interval** of page from one to another. It's for part 3.

**Step 2 : Verify the library**

Check if every package is download.

**Step 3 : Run the code multiple time with different parameter**

If you want to download multiple page of data work from AO3 *you can't do it in one time*.

Once you've done this step you must have a bunch of file called *per example* "base_page_0_to_31","base_page_30_to_61",..."base_page_90_to_121".

Use the part 3 code to mash up every base and you got a unique database of all the work you wanted from AO3.
