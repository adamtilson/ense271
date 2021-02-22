## ENSE 271 - People-Centred Design - Laboratory

# Lab 3: Medium-Fi Wireframes with Adobe XD

### University of Regina
### Faculty of Engineering and Applied Science - Software Systems Engineering

### Lab Instructor: [Adam Tilson](mailto:Adam.Tilson@uregina.ca)

---

## 0. Adobe XD Overview

![XDUI][XDUI]

1. Filename - Save your filename here!
    - The cloud icon means is saved on Adobe's Creative Cloud servers
2. The Hamburger replaces the "File" menu in other apps. On mac, these options are in the menu bar. It includes things like save, open, import, export, etc.
    - importantly you can add libraries, plugins and ui kits here
    - The home menu goes to the welcome splash screen for opening projects  
    - Design is where we'll work in this lab, for putting together 2D designs
    - Prototype allows you to add interactivity to your designs - we'll look at this next lab
    - Share lets you share using creative cloud.
3. These are your standard tools
    - Top is select
    - Next three are drawing primitives
    - You can make lines with the line or pen tool
    - You can add text with the text tool
    - Artboard lets you add more artboards
    - Finally, there are some Zoom tools
    - Outside of the tools here, you can also add images by dragging and dropping them onto your artboard from your file browser
4. The menu down here allows you to change what appears in (5)
    - Libraries let you use Creative Cloud libraries to group together things you commonly use
    - Layers lets you quickly overview your project by seeing the objects nested as a hierarchy. This is a very useful view for finding hard to see things.
    - Plugins add more functionality to XD
5. Here you can use the tool you have selected in (4). 
    - For example, if you have selected libraries in (4), you will find assets here you can drag and drop into your project.
6. Center stage is where you can work on your artboards
    - Artboards are like screens, or pages. It's like an interactive collage where you can drag things around.
    - Artboards have a name, height, width.
    - You can have multiple artboards in one project.
    - You can add, arrange, and delete them as needed.
7. Share, preview and zoom are here. 
    - If you have the Adobe XD app installed on your phone, you can upload previews to it to see how it will work on that device.
    - We'll explore interactivity in the next lab
8.  The properties inspector here allows you to modify the selected element. This includes things like:
    - border and fill colors of primitives
    - font styles
    - some simple effects like blurring and gradients
    - some advanced tools, like Repeat Grid
    - If you want to fine tune an element, and don't know where to look, check here.

One you have place an object on the stage, you can select it with the select tool and left click. Gizmos will appear:

![gizmos][gizmos]

These can be used to resize objects and round corners. You can also rotate around pivot points.

Finally, you can right click on objects to find some more options about it.

## 1. Lo-Fi Prototyping

Adobe XD can be used for lo-fi prototyping.

Lo-fi prototyping, (creating wireframes, or mockups) is the simplest way to roughly lay out the visual elements of your design. These mock-ups are purposefully rough and devoid of detail or color so that one is forced to focus on the structure, and remain uncomitted to the design a site is taking on so that they are open to change.

Dedicated tools exist for this, like Balsamiq, but we can also easily simulate this in Adobe XD.

Baslamiq has a good explanation of [Wireframes here](https://balsamiq.com/learn/articles/what-are-wireframes/).

You can get started [with a UI kit](http://handdrawngoods.com/store/jolly-ui-free-hand-drawn-ui-kit/), or make some simple objects yourself.

Example:

![Lo-fi][Lo-fi]

Let's make some of these elements quickly, and attempt to quickly [prototype one of the pages here](https://balsamiq.com/learn/articles/what-are-wireframes/).

## 2. Medium-Fi Prototyping

In Adobe XD, it's often not much harder to create medium-fidelity prototypes, which involve colors, actual images, and content. We can create our layouts using primitive shapes with color, 

But first we might want to add some things to our project...

## UI Kits

Hamburger -> Get UI Kits -> Apple iOS or Material Design or Windows or whatever

## Finding and using images

To use images in your application, simply drag and drop them in from your file browser. 

A quick note on licensing:

Always make sure that you have the rights to use the images that you use on your website!

The easiest way to ensure that you can use assets for any purpose is to use Creative Commons CC0 assets - this is a very permissive license which effectively puts the assets in the public domain, allowing anyone to use them for any purpose without even needing to credit their source.

## Medium-Fi Example

Let's work through a medium fidelity example. We will try to replicate a website from [Frontend Mentor](https://www.frontendmentor.io/). I have already compiled assets you may want, which you can find in the example files.

Some notes on advanced things we'll look at:

- Repeat Grid

    - When you find yourself repeating an element, it can be a lot of work
    - Repeat Grid is a workflow for creating repetition
        - Example: Gallery, Blog Posts, Cards
    - Start by designing one element which will be repeated
        - You can group the elements together to keep yourself organized
    - With the object(s) selected, click the repeat grid button in the inspector
        - Green grabbers appear on the top and side
        - You can stretch these out and drag in the x or y directions
        - Multiple copies will appear
    - You can adjust the spacing by changing the pink spacing gizmo between copies
        - You can update elements of individual grid elements by clicking and modifying
    - You can update images by selecting a similarly sized one in your file browser, and dragging and dropping onto the target image. You can even do multiple images at once. Cool!
        - Images will be automatically masked – you can double click to fine tune alignment if the auto masking was way off
        - You can also drag in text files to auto-populate titles
    - If you ever need to fine tune things, break the grid! Then all of your elements just become elements again! Cool!

![repeat-grid-gizmos][repeat-grid-gizmos]

- Gradients

    - A simple color effect which is popular online is a gradient, which a is color fill where one color gradually blends into another linearly
        - In order to use, change the fill type from Solid to linear gradient
        - You can choose the color at each end
        - You can also choose opacity at each end
        - You can move the gradient line to change the direction of the blend

## Assignment

Head to the website [Frontend Mentor](https://www.frontendmentor.io/challenges), which includes a number of front end design challenges. Find a free challenge which looks interesting to you, (Recommended difficulty: Newbie to Junior) 
and attempt to create a medium fidelity prototype of it in Adobe XD.

- You may optionally link your GitHub account to download images, but it's not strictly necessary, you could instead look for appropriate CC0 stock images and use them in place. Some designs use only primitives.

- When submitting, provide a link to the challenge you are trying to complete

## Submission

Please submit your Adobe XD file to URCourses by the due date. Please also include screenshots in case the marker has difficulty opening up your XD files.

---

## References

P. Guilizzoni, [What Are Wireframes](https://balsamiq.com/learn/articles/what-are-wireframes/), Balsamiq Wireframing Academy, Balsamiq Studios, LLC

E. Key, [Prototyping a WordPress Project in Adobe XD](https://www.lynda.com/Web-tutorials/Prototyping-WordPress-Project-Adobe-XD/2809592-2.html), Linda from LinkedIn, 2019

[Lo-fi]: res/lofi.png "Lo-fi"
[XDUI]: res/xd-ui.png "XD User Interface"
[gizmos]: res/gizmos.png "Gizmos for resizing"
[repeat-grid-gizmos]: res/repeat-grid-gizmos.png "Repeat grid gizmos"