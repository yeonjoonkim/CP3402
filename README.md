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

# About the Theme
The aim was to deliver the website with the friendly and simple that are visually easy to see on the eyes, As our main target audience is the mature-aged group who is the third age. The provided contents such as text and images have been rearranged and reformatted into a well-thought, organised layout that makes reading through the site better.

# Features
- A simple navation bar at the top
- Comment section on the homepage
- Visual location on the about us

# Theme editting
If you wish to, you can edit the theme using theme using the functionalities provided by Wordpress.
- WP-admin -> Appearance -> Theme Editor
- Wp-admin -> Appearance -> Customize
- Wp-admin -> Appearance -> Menu

#Content editting
You can also change how the website contents are organised by simply editting the pages

# Theme files editting
The main files are in the form of HTML, CSS, Sass, PHP and Javascript. Using an IDE or text editor, you can directly make changes to these files to fir your styling.

# Plug-ins
- [All-in-One WP Migration](https://wordpress.org/plugins/all-in-one-wp-migration/) - Migration tool for all your blog data. Import or Export your blog content with a single click.
