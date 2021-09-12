# Riddler-Can-You-Roll-The-Perfect-Bowl

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.



    In order for Nick’s green bowl to split the two red bowls, he needed
    expert precision in both the speed of the roll and its final angle of
    approach.

    Suppose you were standing in Nick’s shoes, and you wanted to split two
    of your opponent’s bowls. Let’s simplify the math a little, and say
    that each bowl is a sphere with a radius of 1. Let’s further suppose
    that your opponent’s two red bowls are separated by a distance of 3 —
    that is, the centers of the red bowls are separated by a distance of
    5. Define phi as the angle between the path your bowl is on and the
    line connecting your opponent’s bowls.

    For example, here’s how you could split your opponent’s bowls when phi
    is 75 degrees:

    What is the minimum value of phi that will allow your bowl to split
    your opponents’ bowls without hitting them?
    
Plan

I will approximate the solution to this puzzle by simulating the game
from many different angles. Thankfully, because the game is vertically
and horizontally symmetric, I only need to simulate the green ball
reaching the middle point between the red balls and only need to see if
it collides with the top red ball.
