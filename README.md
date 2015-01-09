# Using XPath and XSLT


    1. Download the file xpath.java and edit it to include the following XPath queries. First, download the following XML document along with its DTD that describes journal articles:
        SigmodRecord.xml.
        SigmodRecord.dtd (the DTD of the document). 
    Note: the links are NOT broken. Just right click and use "Save Link As" to save the XML and DTD files on your PC.
        Insert XPath queries in xpath.java that answer the following:
        Print the titles of all articles whose one of the authors is David Maier.
        Print the titles of all articles whose first author is David Maier.
        Print the titles of all articles whose authors include David Maier and Stanley B. Zdonik.
        Print the titles of all articles in volume 19/number 2.
        Print the titles and the init/end pages of all articles in volume 19/number 2 whose authors include Jim Gray.
        Print the volume and number of all articles whose authors include David Maier. (note: we need the number entry of
        an article, not the number of articles). 
    2. Consider the following XML document along with its DTD that describes recipes:
        recipes.xml
        recipes.dtd 
    Write an XSLT program recipe.xsl to display the recipes nicely on a web browser. The XSLT should generate HTML code. You should display all data except the related elements. Use the Java program xslt.java to test your XSLT and then load the resulting html output file on your web browser. 
