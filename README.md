Freelancer Jekyll theme  
=========================

Jekyll theme based on [Freelancer bootstrap theme ](http://startbootstrap.com/template-overviews/freelancer/) and the timeline from [Agency bootstrap theme](http://startbootstrap.com/template-overviews/agency/) 

## How to use
 #### Header Image
 - Place your Header Background image in `/img/` and change the value of `header-bg` in `_config.yml` to the image name.
 - If you don't want a header image then add a `#` before the `header-bg` to comment it out.
 

 #### BLog
 - To enable or disable the blog, set the `set-blog` in `_config.yml` to `true` or `false`.
 - Create posts to display on your blog.
  
 
 #### Portfolio
 - Place your portfolio images in `/img/portfolio/`
 - Enter your portfolio data in `_data/projects.yml`. Just edit the values from the default file.
```txt
- id: "1"
  title: "Your Project 1 Title"
  pic_name: "cabin.png"         #The full project image inside the model
  icon_name: "game.png"         #image shown in the grid.
  description: "Project 1 Description."
  points: 
    - title: "Client:"
      links:
        - title: "The Client"
          href: https://startbootstrap.com/template-overviews/freelancer/
    - title: "Date:"
      links:
        - title: "December 2016"
          href: "#"
    - title: "Service:"
      links:
        - title: "Web Development"
          href: https://startbootstrap.com
```

 - Keep in mind you can add as my links as you want, say For example you want to add another link to a service. Then just add another `title` and `href` under the first one.
 - Or you want to add another point, such as Languages used for Project. Then just add another `title` and `links` .
```txt 
 points: 
    - title: "Client:"
      links:
        - title: "The Client"
          href: https://startbootstrap.com/template-overviews/freelancer/
    - title: "Date:"
      links:
        - title: "December 2016"
          href: "#"
    - title: "Service:"
      links:
        - title: "Web Development"
          href: https://startbootstrap.com
        - title: "Service 2"
          href: https://example.com
    - title: "Languages Used"
      links:
        - title: "C#"
        - href: linkToC#.com
        
```


 #### Experience/Timeline
 - Place your images in `/img/timeline`
 - Enter your timeline data in `_data/experience.yml`. Just edit the values from the default file.
 - The following example is for the item on right side of timeline. For left side leave the class blank. i.e `class: ""`.
```txt

- class: "timeline-inverted"
  icon: "2.jpg"
  icon-alt: "alternate text for image"
  title: "Your Experience Title"
  sub_title: "Some cachy title"
  description: | 
        Description for your Experience. 
        Can expand to multiple lines <br>
        Write whatever you want.<br>
        If you want a paragragh then remove the `br` tags .<br>

```

 
## Demo
View this jekyll theme in action [here](https://digvijayad.github.io/freelancer-theme)

## Screenshot
![screenshot](https://raw.githubusercontent.com/digvijayad/freelancer-theme/master/screenshot.png)

---------
For more details, read the [documentation](http://jekyllrb.com/)