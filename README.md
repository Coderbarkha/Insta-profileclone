 Instagram Profile Page Clone

This project is a clone of an Instagram profile page, built with HTML and CSS.
It replicates the appearance and layout of an Instagram profile page, including features such as a user profile section, bio, posts grid, highlights, and action buttons like follow and message.

 Features

- Profile Section: Displays user profile image, post count, followers, and following count.
- Bio Section: Showcases a sample bio with current location, website link, and collaboration request.
- Action Buttons: Includes a follow button that can change to "Following," a message button, and an option to add friends.
- Highlights Section: Contains a row of highlight images.
- Posts Grid: Displays a grid of post images.
- Tab Icons: Switches between Posts, Reels, and Tagged sections.

 Technologies Used

- HTML: Used to structure the page layout.
- CSS: Used for styling, including the Instagram-like gradient background, borders, and shadows.
 Setup Instructions

1. Clone this repository to your local machine.
   git clone https://github.com/your-username/instagram-profile-clone.git
2. Navigate to the project directory.
3. Open `index.html` in your browser to view the profile page clone.

 Files

- `index.html`: The HTML structure of the profile page.
- `style.css`: The CSS file for styling the profile page.

 Code Explanation

- Gradient Background: The Instagram gradient is applied to the entire background using CSS:
   css
   background: linear-gradient(to right, #f58529, #f77737, #ec008c, #d3007d, #9b2e9f);
- Container: The profile page is contained within a `.container` div with a fixed width and a white background to prevent gradient bleed into content.
- Profile Section: Displays the user's profile image, post count, follower count, and following count.
- Bio Section: Shows the user’s name, bio, location, and website link.
- Follow and Message Buttons: Interactive buttons styled to match Instagram’s colors.

 Customization

You can replace placeholder images and text with actual user data to make it look like a real Instagram profile page. Update the text within the `<div class="insta-bio">` section to add your custom bio.

 Future Improvements

- Add JavaScript to allow dynamic changes to the "Follow" button.
- Include additional CSS animations for smoother interactions.
- Make the page responsive for better mobile compatibility.

 License

This project is open-source and available under the MIT License.
