# CP3402 U3A Project

## Project

The theme is based on the understrap starter theme template and used the theme for a U3A Townsville Insitution website for the JCU subject CP3402. The deployment setup used the two different types of apporach by using the local host and live website hosting via google cloud.

# Requirement
- Scotch Box
- Wordpress

# Deployment

1. Set up the local scotch box by using the command on the terminal
- git clone https://github.com/scotch-io/scotch-box U3A

2. Download the Wordpress 
- https://en-au.wordpress.org/download/
- Unzip the package on the public in the U3A Public

3. Delete the wp-content in the wordpress

4. Command following step to deploy the Themes and Plug-in
- U3A
- Public
- "Wordpress-file-name"
- git clone https://github.com/yeonjoonkim/CP3402-U3A.git wp-content

5. Turn on the vitural machine by using the command
- "Vagrant up"

6. Open the website
- 192.168.33.10/wordpress/

# Plug-ins

- [Child Theme Configurator](https://wordpress.org/plugins/child-theme-configurator/) - Create child themes and customize styles, templates, functions and more.
- [All-in-One WP Migration](https://wordpress.org/plugins/all-in-one-wp-migration/) - Migration tool for all your blog data. Import or Export your blog content with a single click.
- [Elementor](https://wordpress.org/plugins/elementor/) - The Elementor Website Builder has it all: drag and drop page builder, pixel perfect design, mobile responsive editing, and more.
- [Elementor Header & Footer Builder](https://wordpress.org/plugins/header-footer-elementor/) -This powerful plugin allows creating a custom header, footer with Elementor and display them on selected locations. 
- [PDF Embedder](https://wordpress.org/plugins/pdf-embedder/) - Embed PDFs straight into your posts and pages, with flexible width and height. No third-party services required.
- [Wonder Slider Lite](https://wordpress.org/plugins/wonderplugin-slider-lite/) -WordPress Image and Video Slider Plugin
- [WP Google Maps](https://wordpress.org/plugins/wp-google-maps/) - Create custom Google Maps with high quality markers containing locations, descriptions, images and links. 
- [WPForms Lite](https://wordpress.org/plugins/wpforms-lite/) -  Use our Drag & Drop form builder to create your WordPress forms.

# About the Theme
The aim was to deliver the website with the friendly and simple that are visually easy to see on the eyes, As our main target audience is the mature-aged group who is the third age. The provided contents such as text and images have been rearranged and reformatted into a well-thought, organised layout that makes reading through the site better.

# Features
- A simple navation bar at the top
- Comment section on the homepage
- Visual location on the about us

# Theme editting
If you wish to, you can edit the theme using theme using the functionalities provided by Wordpress.
- WP-admin -> Appearance -> Theme Editor
<img width="595" alt="2021-07-14 01 00 32 am" src="https://user-images.githubusercontent.com/68950976/125475390-accbac91-7545-4407-a162-b7093cc21b91.png">


# Customizer
- Wp-admin -> Appearance -> Customize

<img width="595" alt="2021-07-14 01 00 32 am"  src="https://user-images.githubusercontent.com/68950976/125474890-edc3606c-d38e-4627-a6a4-21034168ed0c.png">

# Menu
- Wp-admin -> Appearance -> Menu
<img width="595" alt="2021-07-14 01 00 32 am"  src="https://user-images.githubusercontent.com/68950976/125474629-6b4be861-fc53-4ec3-8086-897f8ba4ce6b.png">


#Additional CSS
- Wp-admin -> Appearance -> Customize -> Additional CSS
<img width="595" alt="2021-07-14 01 00 32 am"  src="https://user-images.githubusercontent.com/68950976/125474307-564b9ce9-50c8-4bb6-919f-d0ecda182e41.png">

#Content editting
You can also change how the website contents are organised by simply editting the pages

# Theme files editting
The main files are in the form of HTML, CSS, Sass, PHP and Javascript. Using an IDE or text editor, you can directly make changes to these files to fir your styling.
