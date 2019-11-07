# WorleyNoise
A Worley Noise Generator in vb.net
Worley noise is a distance based noise algorithm useful amongst other things for generating cell or rock like textures.


Yes I made a typo :(

Final update 5/11/19

Now works with any N value but is capped at N=64.
Also added an option to use an alternate noise formula made up by me (though Im sure its not original) 
It needs N to be 3 or higher and produces cobblestone like patterns at low n values.

Formula is: take the positive of the following (n1-(max n/2))+ (n1-max n)

eg. if n=10 
Then Abs((n1-n5)+(n1-n10))


ps.(not implemented in the code)
(n5-n1)+(n10-n1)
is faster and does the same :)
