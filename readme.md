# MOOMET

MOOMET isn’t a  framework, yet. It is grid and typography system. 

## Background

### Grid
The grid system is built from Susy 3. Unlike the grid system from popular css frameworks, we use different total columns on every screen (desktop, tablet and mobile), it’s Susy approach, btw. By default we use 12 columns for desktop, 8 columns for tablet, and 4 columns for mobile.

### Typography
Typography, typography it’s the hardest thing when we decide to build this system. We read and learn about good typography but so far I haven’t seen somebody talk about a good typography on responsive web design. We don’t talking just about responsive typography, a good typography is beyond that. It’s not only about changing font size and/or line height but also we need to find the key how to define a good typography, and find the formula.

I’m not sure that this is the 100% right answer but Character per Line (CPL) is one of the key. So we go with different approach. Most of responsive typography framework use view port as reference to scale font properties. But on MOOMET we use container width as reference, because we care about CPL.Thanks to Tom Hodgins who create EQCSS, so we can achieve this goal.

## Credit
1. [Susy](http://susy.oddbird.net/) – to build grid system
2. [EQCSS](http://elementqueries.com/) – to define element query
3. [Modular Scale](modularscale.com) – 	for [meaningful typography](https://alistapart.com/article/more-meaningful-typography)
4. Highly inspired by Bootstrap 4!