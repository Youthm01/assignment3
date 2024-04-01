
# Website Documentation

## Overview

This website, created by Man Yang, showcases my programming skills, projects, and personal journey in the IT sphere. It aims to share my work, insights into programming, and a bit of my personality, hoping to connect with like-minded individuals and potential opportunities in the IT industry.

## Directory Structure

- `/`: Root directory containing the main HTML files.
  - `index.html`: Homepage introducing me, my interests in programming, and a brief about my personality.
  - `projects.html`: Lists various projects with descriptions, technologies used, and their functionalities.
  - `blog.html`: Features articles on coding learnings, tips, and technical viewpoints.

- `/css`: Contains CSS files for styling the website.

- `/img`: Directory for images used across the website.
  - `favicon.ico`: Website favicon.
  - `profile.jpg`: A portrait of Man Yang used in the introduction section.
  - `blog.jpg`: Represents the blog section.
  - `skills.jpg`: Showcases the skillset Man Yang possesses.



### Code Snippets Documentation
#### 1. Navigation Menu
```html
<nav>
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="projects.html">Projects</a></li>
        <li><a href="blog.html">Blog</a></li>
    </ul>
</nav>
```
- **Purpose**: Provides a navigation menu on the website, allowing users to easily navigate to the Home page, Projects page, and Blog section. Placed typically at the top of every page for consistent site navigation. Requires CSS for styling. Embedded within the `<body>` tag of HTML documents.

#### 2. YouTube Video Embed
```html
<iframe width="250" height="140" src="https://www.youtube.com/embed/MZEDpuQdDag" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```
- **Purpose**: Embeds a YouTube video into the webpage, offering a multimedia element to engage visitors. Used to showcase video content related to the site's content, such as a project demo. Can be placed within any section of a webpage where video content is relevant.

#### 3. Footer with Contact Information
```html
<footer>
    <p>Contact me: <a href="mailto:mn932850@dal.ca">mn932850@dal.ca</a></p>
</footer>
```
- **Purpose**: Provides a footer section for the website containing contact information, enhancing website accessibility and user engagement.bPlaced at the bottom of every webpage. Requires CSS for styling.

#### 4. Page Metadata and Favicon
```html
<head>
    <meta charset="UTF-8">
    <title>Home - My Programming Portfolio</title>
    <link rel="icon" href="img/favicon.ico" type="image/x-icon">
</head>
```
- **Purpose**: Sets up the character encoding, page title, and favicon for the website, crucial for web standards and branding. Included within the `<head>` section of each HTML document. The favicon file (`favicon.ico`) needs to be placed in the specified path.

#### 5. Linked Image to External Content
```html
<a href="https://content.techgig.com/technology/top-8-programming-blogs-that-every-software-developer-must-read/articleshow/77672235.cms"><img src="img/skills.jpg" alt="Skills Image" width="100" height="100"></a>
```
- **Purpose**: Provides an image link to external content, in this case, a programming blog, which serves as a resource or further reading. Can be used in blog sections or resources page to link to external authoritative content. Requires the image (`img/skills.jpg`) to be present in the specified path.

#### 6. Video and Audio Embed
```html
<video controls width="250">
    <source src="videos/introduction_video.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
<audio controls>
    <source src="audio/intoduction_audio.mp4" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>
```
- **Purpose**: Embeds video and audio clips into the webpage, providing a rich media experience for the user. Used for introducing the website owner or showcasing multimedia presentations. The video (`introduction_video.mp4`) and audio (`introduction_audio.mp4`) files need to be stored in the specified paths.

#### 7. Profile Image and Projects Table
```html
<img src="img/profile.jpg" alt="Professional Headshot" width="200" height="200">
<table>
    <tr>
        <th>Project Name</th>
        <th>Technologies Used</th>
        <th>Link</th>
    </tr>
    <tr>
        <td>🖥 FRONT END CHALLENGES OR SKILLS</td>
        <td>HTML, CSS</td>
        <td><a href="https://github.com/iamismile/web-dev-resources?tab=readme-ov-file#-front-end-challenges-or-skills">View Project</a></td>
    </tr>
</table>
```
- **Purpose**: Displays a professional headshot and a table listing projects with technologies used and links to view the projects.Utilized in about or portfolio sections to showcase professional image and detailed project information. Requires the profile image (`img/profile.jpg`) to be present in the specified path and CSS for styling the table.

#### 8. 

## External Sources

[1]	fayefilms. 2023. First day of university and I’m already tired. Retrieved February 9, 2024 from https://www.youtube.com/shorts/MZEDpuQdDag
 	 
[2]	Ismile Hossain. web-dev-resources: The complete web development resources you ever need. More than 150+ resources for your web development.
 	 
[3]	Istockphoto.com. Retrieved February 9, 2024 from https://media.istockphoto.com/id/1318327528/photo/charming-asian-businesswoman-working-with-a-laptop-at-the-office-looking-at-camera.jpg?s=612x612&w=0&k=20&c=t-DTh02iSEXHea_5ZV0hnuw-8KCMz3Z9Ki4slzQkulk=
 	 
[4]	Techgig.com. Retrieved February 9, 2024 from https://contentstatic.techgig.com/photo/77672235/top-8-programming-blogs-that-every-software-developer-must-read.jpg?150543
 	 
## Contact

Man Yang
Email: mn932850@dal.ca








