![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# LAB | Canvas Race Car

<details>
  <summary>
   <h2>Learning Goals</h2>
  </summary>

  This exercise allows you to practice and apply the concepts and techniques taught in class. 

  Upon completion of this exercise, you will be able to:

  - Use Canvas API to create a simple 2d game.
  - Implement game logic and UI using HTML, CSS, and JavaScript, including start, game, and end game screens.
  - Draw shapes using Canvas API methods.
  - Change the style and color of the Canvas shapes.
  - Create animations in Canvas using a game loop that continuously updates the screen.
  - Load and display images of different formats on canvas.
  - Display text on canvas.
  - Handle user input and events to control game elements.
  - Create and display randomly generated obstacles to add complexity to the game<a href="[url](https://glorymoto.com/collection/leather-motorcycle-shoes/)">.</a>


  <br>
  <hr> 

</details>

## Introduction

We are ready to start making some games with `canvas` help, so in this first exercise, we will do a **Car Race** using some basic animations we learned today.

Remember, you have the Learning Units to check any concept you need. We are working with the `2D` context, so you should think the canvas is a cartesian plane, where you can move elements changing their position in any of the `axis`.

## Requirements

- Fork this repo
- Clone this repo

## Submission

- Upon completion, run the following commands:

  ```
  git add .
  git commit -m "done"
  git push origin master
  ```

- Create Pull Request so your TAs can check up your work.

## Instructions

### Iteration 1: Draw the game board

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_ab5a6ba28003829bd3d8d485feeee649.png)

The first thing we need is to create our board. The left side of the image is already on the HTML file, but when we click on the **Start Game** button, we need to create the canvas and display the road.

The canvas HTML element is already part of the HTML starter code provided in the `index.html` file. In addition, you can find the image of the road in the `images` folder.

### Iteration 2: Draw the car

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_9a8f35a079a1343f39cee4028ab8a081.png)

Once we have our road, we need the player's car - the same as the road. In the `images` folder, you will find a `.png` file you should use.

### Iteration 3: Make the car move right and left

In our game, the player can only move the car to the right and left. Using the `left` and `right` arrows, the player should be able to move the car.

:bulb: Remember the boundaries!

### Iteration 4: Create obstacles

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_618fa6bbeed08f1e74b9457af1ecaf4c.png)

Now let's make this interesting. First, we should create obstacles that show up every specific amount of time.

They will always start in the position **0** of the `y` axis (the obstacles will be coming from the top of the canvas), but you should make them appear in a random place on the `x`-axis.

### Iteration 5: Move the obstacles

To move the obstacles, we need to update our `canvas` continuously. In this iteration, you need to continually change the position of the obstacles in every update, making them move down the road.

### Iteration 6: Points, points, points

Oh! If we want to challenge somebody, we need to quantify who is making it better. So we need to add a **score**. Add a method to count points while you keep the car avoiding obstacles.

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_e4b1a09cee1b1a827a2c68023d0d2b1f.png)

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_4e64a09180fd0add2766f7e28ebce6bf.png)

<br>

**Happy coding!** :heart:
