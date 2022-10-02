# Welcome to Janav's page

I was introduced to programming because of a ***buring desire*** to make video games. 

> I was not able to make any video games because I was not very good at art.
> After speaking to people at UCSD I found this meme to be very accurate.
![Got this image from Reddit](https://preview.redd.it/1pxgsysejuu81.gif?format=mp4&s=e482610240b1bf32bd273dc7733e0551716737a0)

Here is a random quote I found on the internet
> Opportunities don't happen, you create them

I like interesting and clever solutions to problems.
Here is some code in c++ to calculate the inverse of the square root ofa number from the original Quake III arena (taken from [here](https://github.com/id-Software/Quake-III-Arena))
```
float Q_rsqrt( float number )
{
	long i;
	float x2, y;
	const float threehalfs = 1.5F;

	x2 = number * 0.5F;
	y  = number;
	i  = * ( long * ) &y;                       // evil floating point bit level hacking
	i  = 0x5f3759df - ( i >> 1 );               // what the fuck? 
	y  = * ( float * ) &i;
	y  = y * ( threehalfs - ( x2 * y * y ) );   // 1st iteration
//	y  = y * ( threehalfs - ( x2 * y * y ) );   // 2nd iteration, this can be removed

	return y;
}
```
This code was used in a game engine to approximate the inverse of a square root quickly. The code gives up some accuracy in favour of speed. 
More information on this code can be found in this [video](https://www.youtube.com/watch?v=p8u_k2LIZyo).

Here is an unordered list of the new graphics cards launching soon.
- Nvidia RTX 4090
- Nvidia RTX 4080 (16GB)
- Nvidia RTX ~~4070~~ 4080 (12 GB)

Here is a ordered list of my favourite games
1. Witcher 3
2. Cuphead
3. Hades

Here is a task list of things I plan to do this quarter
- [X] Join a club.
- [ ] Do a project.
- [ ] Raise my GPA.

Here is a [link](/README.md) to an other md file from master.

Thank oyu fro reading all this.
Here is a link to go back [up] (# Welcome to Janav's page)