### IMPROVED STYLING WITH CSS
# Pinpoint E-Commerce
In this project, you will use the knowledge you gained within the Color for UI lesson and apply it to an e-commerce checkout page. You will take an existing grayscale website and apply colors to various elements and sections within the design to ensure users understand the error and active states as well as primary calls-to-action.

This means you will need to consider which elements need to be updated based on providing the user with enough information to continue adding their information to complete their checkout process.

Remember, it’s important to use colors that will help them make the right decisions and provide feedback they can adequately act on.

Please note the workspace example on the right is built to fit into the viewing area. If you increase and decrease the viewable area of the web site, the site will update and respond to the viewport’s dimensions.

Task:

Tasks
0/13 Complete
Mark the tasks as complete by checking them off
1.
First, let’s start by adding some basic contrasting colors to our site. This will allow the main site navigation content and hero content to be legible to all users.

Let’s update the backgrounds of the CSS selectors .site-header and .site-main-background from #EBEBEB to #34474F.

The site-header selector can be found in the Modules Styles section of the stylesheet while the .site-main-background can be found in section 6, Page Styles.


2.
Great, now that the backgrounds of your navigation and hero section are dark, we need to update our text colors. This will allow our users to see the text without facing any issues.

A fairly common color designers use in this situation is white. By updating our text from black to white, we will provide users with an optimal reading experience.

In your styles.css file, find .site-main-header h1 and .site-main-header p. Update their color property to from it’s current color to white.

Both of these selectors can be found in section 6, Page Styles.


3.
Lastly, let’s make sure our navigation elements are clearly visible for our users. Let’s update the color of our links from gray to white. Find the selector .site-nav-link in section 4 of our stylesheet.


4.
Now let’s give our site a little flare. As you can tell from the site’s logo, yellow is one of the main brand colors for PinPoint. Let’s introduce this color so it starts to resonates with users.

One place we can do this is in the navigation. Let’s make the active link reflect our brand’s yellow. The yellow hexadecimal value is #FFAA00.

The selector you will need to edit is .site-nav-link.active and can be found in section 4, Modules Styles, of the stylesheet.

Note: If you do not see the navigation links in the workspace, feel free to pull your workspace browser to the left to increase its viewport size. This site is mobile responsive and hides and shows elements based on the screen’s size.


5.
Alright, the top part of the site is starting to take shape. Now let’s work on its spacing. Whitespace is an important design aspect because it provides natural breaks and allows the user to distinguish what goes together.

Let’s start by adding better spacing to our site’s hero section. Increase the top and bottom padding of CSS selector .site-main to 60px. This selector can be found in section 6, Page Styles, of the stylesheets.

Then within the .site-main-header, update the bottom margin to 60px. This CSS selector can be found in section 6, too.


6.
Now, let’s increase the size of our workspace’s viewport. Once the navigational elements appear you can stop. Notice how close the links are together? This is not a good user experience.

Let’s fix this by targeting the link elements and give them margin to only one side, the right. In section 4, Modules Styles, of your stylesheet location the selector group of:

.site-nav-left li:not(:last-child),
.site-nav-right li:not(:last-child),
.site-nav-mobile li:not(:last-child) { }
and update spacing property that is being used so it spaces the elements apart by 30px.

Note: we are using a few pseudo-selectors. The first :not() looks at all of li elements in its respective list and then applies a specific CSS property to each li that is not :last-child or last list item.


7.
A good way to provide visual breaks on a website is by using horizontal lines. However, we want to make sure our horizontal lines don’t run into our other content.

Let’s add 20px of space to the outside of our .divider selector. You can find this selector in section 3, Structure Styles, of our stylesheet.


8.
Now let’s add some whitespace to our items we are ordering. Again we are going to add space to the top and bottom of these elements. Go ahead and add 50px of space to the .order-item selector.

This selector can be found in section 6 of the stylesheets.


9.
Alright, now our spacing is looking good. Next, we want to style our interface components so they provide our users with visual cues.

First, let’s add some color to alert on the page. Since this alert is warning the user they failed to fill something out it makes sense to make it red. While we can’t just rely on color to indicate an issue, it is best practice for error messages to be red and success message to be displayed in gree.

Let’s up the background of the alert selector .alert-error to #FC472E. You can find this selector in section 5, Component Styles.


10.
Great so we alerted the user that something went wrong with an alert component, but now we need to visually show them where the issue is on the page.

We can do that on this form by adding some color to the input that caused the error. Let’s target the :active pseudo-selector for the input and change the border color to the same red we used on the alert. The input component can be found in section 5 of our stylesheet.


11.
One of the most commonly used components on any web site is buttons. They tell users where to click and how to navigate from page to page or submit information.

On our site we have two buttons, button-primary and button-secondary, we use. The first button is used for page actions and form submissions, while the later is actions that are not page specific, like links or calls to action.

Let’s update the button’s background colors to reflect our site’s branding. The button used on the page should have a background color of #00CF63. The button used for navigation or non-essential actions should use the hexadecimal of #FFAA00.

You can find these selectors in section 5 of the stylesheet.


12.
If you take a look at our web site you will notice we provided some information for our users to contact a customer support team if they are facing issues. However, it seems as if it is blending into the site. Let’s make this stand out from the form so users can find it easily.

One way we can do that is by adding some whitespace to the element and changing the element’s background.

Let’s add 30px spacing to the outside of the selector, .help-box, 15px of spacing to inside of the element and making the background #FFAA00.

You can find this selector in section 6 of our stylesheet.


13.
Awesome. Our help box is starting to look great. Now, let’s make sure we make it clear that the telephone number in the help box is clickable.

Let’s target our a selector and update it’s color to #42A5F5. You can find this selector in section 2 of our stylesheet.