# fitting_least_square_rectangle

Fitting a rectangle using least square distance in set of 2D points

It starts with the minimum bounding rectangle. (minimum area rectangle that encloses all the points.

![image](https://user-images.githubusercontent.com/67344167/218549662-ffe63ffb-0d55-467d-8937-164f5164c1ef.png)

Then the function tries to converge the rectangle to least square distance rectangle. (Sum of suares of distance of points from the lines is minimum) We create a loss function as sum of square distance and implement gradient decent to optimize it.

![image](https://user-images.githubusercontent.com/67344167/218550380-1bcecfe7-bbc5-4b23-aed4-7b455b15a337.png)

You can try running the code on google colab https://colab.research.google.com/drive/1VyxJGLfKkzFuN-MF_38J-Y_RqrZ19bVz#scrollTo=0PZ7DSofImzo
