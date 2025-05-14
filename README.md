<a href="https://www.repostatus.org/#active" target="_blank" Title="Project Status: Active – The project has reached a stable, usable state and is being actively developed."><img src="https://www.repostatus.org/badges/latest/active.svg"></a> 

# Sword Module Text Extraction

This notebook in this repository demonstrates how to extract Biblical text from Sword modules using the [`pysword`](https://pypi.org/project/pysword/) library in Python. The `pysword` library provides an interface for accessing and parsing text from [Sword Project modules](http://crosswire.org/sword/modules/), which are widely used for digital Bible resources. In this example, we will load one Sword module and extract the the surface text for a specific book, chapter, and verse, and showcase how to display the extracted content. 

For more information about the Sword Project, visit [The CrossWire Bible Society](http://crosswire.org/sword/).

Also take into account the following comment from: [www.crosswire.org/faq](https://www.crosswire.org/faq)
>
> How do I convert Sword modules to text?
>
> We would like to discourage this. Please work with us in making our software better.
> 
> But, if you really need the text, each module has a conf file which will tell you about the origin of the text. Please obtain the source the same way we did. You may not convert the modules that have been licensed > to CrossWire for distribution. The KJV module is the only one for which we maintain the source, which you can obtain here.

An overview of available modules is available [here](https://crosswire.org/sword/modules/ModDisp.jsp?modType=Bibles).
