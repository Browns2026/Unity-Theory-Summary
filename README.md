# Unity-Theory-Summary
Daily Note

### @22 May, 2026
1. transform.position
    - transform the object
        - Unity Engine doesn't know why the object has been moved
2. linearVelocity
    - Move the Object every second
        - Calculating by Unity Physics Engine working for speed, gravity, collision, etc,.
        - Usually  works with Jump, Knock Back, Sliding, Gravity, etc,.


The importance thing is that working object and Rigidbidy with transform.position at the same time will bring any kind of troble shootings such as 떨림, 충돌이상, 관통, 밀림오류.

So, in the game environment, the game developers use
- linearVelocity for movement
- AddForce or velocity for jump

