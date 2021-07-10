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
