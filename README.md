# Nortal-Summer-University-2022

Welcome to Nortal Summer University 2022 Q/A thread. <BR> 
  
<h4>Hummingbird Travel</H4>
Hummingbirds are tiny birds that can travel about 2200 kilometers without having to stop. It’s about 29 million
times the length of their body.<br> Meanwhile, the marathon-trained developer has a ratio of around 25 thousand.<br>
You’re a curious traveler who found a strange species of these little birds. When gathered, they seem to form
a rectangular shape.<br> It moves in a strange, but beautiful and organized way. You notice the patterns and
understand that it’s a game! As a passionate developer, you start to think about the algorithm that is happening
here. You decide to calculate how long this ‘dance’ will last.<br>
<h4>Game Rules</h4>
• The map consists of squares stored in a TXT file (see src/main/resources/ hummingbird_map.txt).
• The map is always rectangular-shaped of size M x N.
• 0 < M <= 100,000
• 0 < N <= 100,000 <br>
• Only one bird occupies one square of the rectangular grid at one point in time.
• There are empty squares (.) Existing squares that are not occupied by a hummingbird.<br>.
• There are gaps in the map (x).Non-existent squares/holes in the map.<br> 
• There are two types of hummingbirds. Ones moving right (>) and ones moving down (v).<br> 
• Each bird moves in straight lines (one direction) only.<br>
• When crossing the border of the playground, the hummingbird gets straight to the other end of the
current position. (You can hardly even notice it; They are so quick!).
• Right-facing birds move first. They first evaluate if the next square is empty and then move
simultaneously,
• Down-facing birds move second. They first evaluate if the next square is empty and then move
simultaneously,
• If the birds never stop moving, print the number of iterations, when you see the first repetitive
composition. Previously seen arrangement of birds on the ‘game board‘.
Other Requirements
• The application should not be communicating with the console
• You can’t make any changes in the HummingbirdGame.java file
  
