# frontend-mentor-project
This is a warehouse of projects from frontend mentor.

## Stats Preview Info Card
This project is built in HTML and CSS. The card is a simple ui component that gives statistics information. It has a information section and a image. The image has a tint accent that matches the tint of the card theme. After working up the concept and making it responsive, I used a aws s3 bucket to make it live for inspection. Live preview [here](http://stat-card.s3-website.us-east-2.amazonaws.com). I first laid out the html. I then created the css. After getting the css responsive I run it through the [wc3 css validator](https://jigsaw.w3.org/css-validator/#validate_by_uri). Then I used the [autoprefixer](https://autoprefixer.github.io) to ensure my css works on other browsers.

<img src="images/ui-stats-card.png">

### Layout
The design was created to the following three widths:
- desktop
- 1000 px tablet / desktop
- 500px mobile good for 375px

#### Color
Primary
- body bg color #023047 dark blue
- card body #fff3a6 light yellow
- text hl #da7f00 dark orange

Secondary
- text color #0F0F0F

#### Font
Used Google Font for this project.
[Nunito](https://fonts.google.com/specimen/Nunito)
- weights 400, 700, 800