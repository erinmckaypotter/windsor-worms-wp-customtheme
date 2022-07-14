# Windsor Worm Farm
## WordPress X Understrap Custom Theme

Website for a local organic fertilizer business in Windsor, CA.    [Link to Site](https://dev-windsor-worm-farm.pantheonsite.io/)

Built using [WordPress.org](wordpress.org) & [Understrap Theme Framework](https://understrap.com/) 

### Use this Theme Customization

This repo contains 2 Sass files needed to style a WordPress X Understrap site like [Windsor Worm Farm's](https://dev-windsor-worm-farm.pantheonsite.io/).

1. Create your WordPress.org site
2. Install Understrap theme
3. Activate Understrap child theme
4. Access your WordPress files via SFTP connection ([such as Cyberduck](https://cyberduck.io/))
5. Follow this file structure to find your 2 sass files:
    ````
      wp-content
      
         └ themes
         
            └ understrap-child
            
                └ src
                
                   └ sass
                   
                      └ theme
                      
                          ├ _child_theme_variables.scss
                          
                          └ _child_theme.scss
  
6. Replace these **_child_theme_variables.scss** & **_child_theme.scss** with the content of the files in this repo. 
7. Alter the styles to suite your own needs :) (*But do not change the file names or file structure*) 
