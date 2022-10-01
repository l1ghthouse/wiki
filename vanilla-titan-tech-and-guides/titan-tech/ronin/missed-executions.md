---
description: Ronin's melee attack will sometimes fail to execute Doomed Titans.
---

# 🟥 Missed Executions

When a doomed Titan is hit by a melee attacks, the game checks if 3 things are true: is there too much vertical distance, too much horizantal distance, and is there an obstacle in the way. The horizontal disance is set to 350, meaning titans outside of that range who are melee-ed will not be executed.\
\
The issue lies in that this distance of 350 is the same for all Titans, including Ronin. While other titans have quite a bit of leeway between their melee's range and the maximum execution distance, Ronin's Sword has a range of 325. Because melee hits are based on client+server, but terminations are only server-side, the faster an opponent is moving backwards, the closer the Ronin will be to terminate. The laggier the opponent, the more they will be effected by this. However, even opponents with no lag can avoid being executed by the tip of Ronin's sword simply by walking backwards. While there is no way to consistently avoid this, simply getting into the range of a normal titan's melee will make executions much more consistent.

{% embed url="https://www.youtube.com/watch?v=LXm12VkYNb4" %}
Footage of this happening in game at 1:33. A Phaseboost is utilized to get into execution range, but because they were only hit by the very tip of the sword and walking backwards, the Titan was hit but not executed.
{% endembed %}
