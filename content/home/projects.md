+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "Projects"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "project"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  # [[content.filter_button]]
  #   name = "All"
  #   tag = "*"
  
  # [[content.filter_button]]
  #   name = "Deep Learning"
  #   tag = "Deep Learning"
  
  # [[content.filter_button]]
  #   name = "Other"
  #   tag = "Demo"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

Ottawa Walks is now available on ARIS

Project Paradata:

Introduction

This project will be using Aris to lead users on a journey through downtown Ottawa to Parliament while exploring the history of political walks, marches, and runs in Canada. My process has largely been one of trial and error. I started out with a basic idea of what I wanted the user to experience: a progressive exploration of downtown Ottawa through repositories of historical information that allows the user to discover hidden narratives. My project has undergone a lot of change over the course of this semester. It did not start out as an exploration of political walks in Ottawa. Originally, I wanted to achieve this through a game centering on the assassination of D’Arcy McGee.

Concept

The step in this project was finding a digital platform that would be able to accommodate my goals for the project but still be within my skill level. I tried Twine and Taleblazer for the narrative structure. I also played around with a digital atlas for the placement of the repositories. Ultimately, I landed on Aris. It has quite a bit of flexibility in how you can construct your digital overlay of a physical space but it is still very easy to use. However, I have still some issues with Aris. For example, it is only accessible through iOS (Apple devices) and so is not accessible to the general population. As the class read in Bethany Nowviskie’s “Resistance in the Materials,” technologies and the information within them must be accessible, especially to under-represented groups. Additionally, by building my project on an Apple-exclusive platform, I am also condoning if not supporting the environmental and social impacts of Apple products.

Once I had decided on the digital technology that I was going to use for my project, I began to think a bit more about how the tech shaped my subject. After some consideration and consultation with the London Charter, I decided that my subject did not suit the project I was trying to build. The murder mystery narrative just was not fitting into the platform as neatly as I had hoped. I had also had a random thought of another subject that I could not get out of my head. In September, I had visited the Canadian Museum of History and saw an exhibit titled “Footprints” in which I learned about the Journey of Nishiyuu. My random thought had placed that journey to Ottawa right next to my digital exploration framework and it suddenly made so much more sense to change the subject to one of political walks. Before, the idea of having the user walk around seemed a little forced. But with the subject being one of a political walk then the physical exploration of the city, augmented through the digital repositories of historical information, felt much more necessary to the experience.

Development 

With my subject settled on, my next step was to dig in to the research. I picked five walks/marches/runs to have my users explore. They are the On to Ottawa Trek (1935), the Journey of Nishiyuu (2013), the We Demand Demonstration (1971), the Marathon of Hope (1980), and the Climate March (2019). I chose these five because they spanned a range of social issues, political climates, and time. They all also either came to or passed through Ottawa. I later decided to cut out the Marathon of Hope because I felt that it did not quite align with the others given that it only passed through Ottawa. With these walks chosen, I then had to decide what information would go in to the repositories. 

A key issue I experienced when putting the project together has to do with the tailoring of historical sources. I cannot expect people to read through pages and pages of primary and secondary sources while walking around outside. However, by selecting a few short pieces of evidence to illustrate the context and events of each walk I worry that I am over-simplifying and potentially misrepresenting the issues each walk represents. I also did not want to write my own interpretations of the documents because I did not want to insert my own voice into these issues any more than I already had by choosing the subject, the route, and the documents. In the end, for each walk, I decided to include a few news reports on the walk itself, some primary source documents such as interviews, photos, and manifestos/press releases. I purposefully left each story slightly incomplete so as to hopefully inspire the user to further investigate the issues. 

Themes

Aside from the topic of political walks, there are a few themes and concepts that I hoped to explore in my project, one being the convergence between material and immaterial within historical investigation. On one level, we have the medium itself, a digital overlay (immaterial) of historical information on the physical cityscape (material). Allowing the user to both physically and conceptually move through history. Then on another level, we have the actual subject of the political walk in which people walk (material) to bring the social issue (immaterial) they are championing to parliament. Parliament is itself both material, as it is a physical building, and immaterial, as the concepts of state and law. A second concept I was quite excited by was the potential mirroring of a political walk. As political walks progress towards their destination, they typically pick up more walkers. However, in this experience the user or walker, in a sense, picks up political walks/movements.

A final concept that I ultimately decided to explore in response to the qualms I have with ARIS is that of accessibility and privilege in digital media. This theme is not actually represented in the ARIS content itself because I wanted to explore it through de-privileging the content that is gate-kept by an iOS. The walk is only accessible through privilege in multiple ways. For one, ARIS can only be accessed through an iPhone or iPad, meaning that only those who are able to purchase higher-end smart devices can complete the walk. For another, it is after all a walk meaning that only people who are physically able to spend a significant amount of time moving around downtown Ottawa sidewalks can access the full experience. I struggled with how to not only address but also hopefully remedy these issues for much of the semester. That is how I came to decide to privilege the user who visits this website with more information. I do not include any discussion of the larger themes in the ARIS project. Additionally, below, I have included all of the content that is in the ARIS project for anyone who wants to access the information but does not have an iOS device. In terms of physical accessibility, the locations of the repositories can all be visited through Google maps street view and the route can be easily driven.

Conclusion

Over all, I am happy with my project. It is very different from what I had first envisioned both in the steps I took to develop it and in the final subject matter. A large theme that we explored in this class is that of failure. I think that I failed in this project in multiple ways. I failed in developing my original concept. However, in admitting that I was failing to do that subject justice I was able to quickly change my topic to something that I am much happier with. I also failed to actually test my project. One of the quirks of ARIS is that you can build a project on the platform on any computer but you can’t access the user interface of your own game through a computer. As I do not have an iPhone or iPad, I have not been able to actually see what my project looks like from the other side. I think that this particular failure served to inform my understanding of privilege and accessibility in digital media. I don’t think that I would have taken that side of the project as seriously in this paradata if I had had full access to my own project from the beginning. And so, although I am happy with this project I still failed in some ways, but they have been useful, informative failures.

Ottawa Walks Content: shorturl.at/npCGZ 
