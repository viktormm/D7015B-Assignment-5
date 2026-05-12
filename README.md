# D7015B Assignment 5

## Task 1: Ground Level

I used a histogram of the z-values to find the ground area. The ground gives the biggest peak in the histogram because many LiDAR points are reflected from the ground.

Instead of using the exact peak as the cutoff, I use the next histogram bin. This removes a bit more of the ground before clustering.

For Dataset 1: Ground threshold = 61.442
For Dataset 2: Ground threshold = 61.466

<img width="1000" height="600" alt="image" src="https://github.com/user-attachments/assets/f81bb2b7-4e67-4923-809e-b7b49a1ff368" />
<img width="1000" height="600" alt="image" src="https://github.com/user-attachments/assets/9c98ca87-e6fc-4ed2-a4ff-59700cb74875" />


